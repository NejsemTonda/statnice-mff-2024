# Turingův stroj

Truingův stroj můžeme definovat jako uspořádanou sedmici $T = (Q, q_0, (q_-, q_+), \sum, \Gamma, _, \delta)$ kde:

* $Q$: množina všech stavů
* $q_0 \in Q$: počáteční stav
* $(q_-, q_+) \subset Q$: množina přijímaných a odmítaných stavů 
* $\sum$: Abeceda
* $\Gamma \supset \sum$: pracovní abeceda
* _: prázdný symbol
* $\delta: (Q \setminus (q_+, q_-) \time \Gamma \rightarrow Q \times \Gamma \times\{\leftarrow, \cdot \rightarrow\}$: přechodová funkce

Konfigurace Turingova stroje je $(s, \lambda, \pi)$ kde $s \in Q, \lambda \in \Gamma^*$ je stav pásky od hlavy nalevo a $\lambda \in \Gamma^*$ je stav pásky na hlavě a doprava.
