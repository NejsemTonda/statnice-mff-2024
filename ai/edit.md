# Bayesovská síť

* Vrcholy jsou množiny náhodných jevů
* Hrany jsou závislosti proměnných

Vztah ke sdružené pravděpodobnosti: Takto můžeme uvažovat díky řetězovému pravidlu. $P(x_1, \dots x_n) = \prod_i P(x_i | x_{i-1}, \dots, x_n)$

Pro síť `rains -> wet -> slip` se můžeme ptát na pravděpodobnost $P(r, w, s) = P(r) P(w | r) P(s | w)$

Pro síť `rains -> wet <- car wash --> slip` $P(r,w,c,s) = P(r) P(c) P(w | r,c) P(s| w)$

### Inference enumerací

$$P(r|s) = \sum_w \sum_c p(r,w,c,s) / P(s)$$
$$P(r|s) \propto \sum_w \sum_c p(r,w,c,s)$$
$$P(r|s) \propto \sum_w \sum_c P(r) P(c) P(w | r,c) P(s| w)$$
$$P(r|s) \propto P(r) \sum_w P(s| w) \sum_c  P(c) P(w | r,c) $$

To vede na exponenciální složitost protože některé proměné se opakují

### eliminace proměnných

$$P(r|s) \propto \sum_w \sum_c P(r) P(c) P(w | r,c) P(s| w)$$
$$f_c(w) = \sum_c P(c) P(w | r,c)$$
$$P(r|s) \propto \sum_w \sum_c P(r) f_c(w) P(s| w)$$
$$f_w(s) = \sum_w f_c(w) P(s|w)$$
$$P(r|s) \propto \sum_w \sum_c P(r) f_w(s)$$

### Aproxoimace

Pomocí monte-carlo metod
