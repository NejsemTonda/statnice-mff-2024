# Deterministické automaty

**DEF** Automat je definován uspořádanou pěticí 
$$DFA = (Q, \sum, \delta, q_0, F)$$

* Q: množina všech stavů
* $\sum$: abeceda
* $\delta$: přechodová funkce $Q \times \sum \rightarrow Q$
* $q_0 \in Q$: počáteční stav
* $F$: množina přijímaných vrcholů

### Jazyk přijímaný automatem

**DEF** Rozšířená přechodová funkce $\delta^*$
$$\delta^*(\alpha x) = \delta(\delta^*(\alpha), x)$$

Slovo $\alpha$ je přijímáno automatem pokud $\delta^*(\alpha) \in F$


Jazyk přijímaný automatem $A$ značíme $L(A)$
