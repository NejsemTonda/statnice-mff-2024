# Zásobníkový automat

**DEF** Zásobníkový automat můžeme definovat jako uspořádanou sedmici $PDA = (Q, q_0, F, \sum, \Gamma, \delta, z_0)$ kde:

* $Q$: množina všech stavů
* $q_0 \in Q$: počáteční stav
* $F$: množina koncových přijímaných
* $\sum$: Abeceda
* $\Gamma$: Zásobníková abeceda
* $\delta: Q \time \Sigma \cup \{\lambda\} \times \Gamma \rightarrow Q \times \Gamma$: přechodová funkce
* $z_0$: počáteční zásobníkový symbol


**DEF** Stava zásobníkového automatu popisuje trojice $(s, w, \gamma)$, kde $s \in Q$ současný stav $w \in \sum^*$ zbývající vstup a $\gamma \in \Gamma^*$ stav zásobníku

Rozlišujeme mezi PDA, které přijímají prazdným zásobníkem a PDA které přijímájí koncovým stavem.

**THM** PDA s koncovými stavy, PDA přijímající prázdným zásobníkem a bezkontextové gramatiky jsou mezi sebou převoditelné

