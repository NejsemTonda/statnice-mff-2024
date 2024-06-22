# Zpětovazební učení

### Direct utility estimation

Prostě to několikrát zkusíme a spočítáme reward-to-go. Utility jednotlivých stavů odhadneme průměrem.

### ADP
.
Adaptive dynamic programing. Pasivní učení.

Děláme kroky náhodně pomocí naší naučené policy. Pokaždé uděláme policy update. Iterací bychom se měli dostat k optimální policy.

### TD

Temporal-difference learning. Pasivní učení.

Při trénování policy vůbec nepoužíváme, jenom provádíme update utilit.
$$U^{\pi}(s) = U^{\pi}(s) + \alpha(R(s) + \gamma U^{\pi}(s') - U^{\pi}(s)$$

### Q-učení + SARSA

Matice $Q(s,a)$ uakzuje hodnotu provedení akce $a$ ve stavu $s$. To znamená, že $U(s) = max_a Q(s,a)$. Potom můžeme bellmanovu rovnici přepsat na
$$Q(s,a) = R(s) + \gamma \sum_{s'} P(s' | s,a) max_{a'} Q(s', a')$$
$$Q(s,a) = Q(s,a) + \alpha( R(s) + \gamma max_{a'} Q(s',a') - Q(s,a))$$

State-action-revard-state-action (SARSA) pak dělá jenom
$$Q(s,a) = Q(s,a) + \alpha( R(s) + \gamma Q(s',a') - Q(s,a))$$
