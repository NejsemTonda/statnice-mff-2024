# Definice

**DEF** Protor jevů $F \subset P(\Omega0)$ pokud:

* $\emptyset \in F, \Omega \in F$
* Nechápu, co se děje

**DEF** Funkci $F: \Omega \to [0,1]$ nazýváme pravděpodobností, pokud:

* $P(\Omega) = 1$
* $P(A) \geq 0$
* $P(\Cup_i A_i) = \sum_i P(A_i)$

**DEF** Pravděpodobnostní prostor je trojce $(F, \Omega, P)$ taková, že

* $\Omega \not = \emptyset$ je libovolná množina jevů
* $F \subset P(F)$
* $P$ je pravděpodobnost

**DEF** Podmíněná pravděpodobnost, tj. pravděpodobnost $A$ za podmínky $B$ $A,b \in F$ definujeme jako $P(A|B) = \frac{P(A \land B)}{P(B)}$


**DEF** Dva jevy jsou nezávyslé, pokud $P(A|B) = P(A)P(B)$

**DEF** Diskrétní náhodná veličina: Mějmé pravděpodobnostní protstor $(F, \Omega, P)$. Pak diskkrétní veličina je taková funkce $X: \Omega \to R$, pro kterou platí, že $\{\omega \in \Omega: X(\omega) = x\} \subset F$ 

**DEF** Pravděpodobnostní funkce diskrétní náhodné veličiny je fuknce $p_X: R \to [0,1]$ taková, že $p_X(x) = P(\{X = x\})$

**DEF** Očekávanou hodnotu náhodné diskrétní veličiny definujeme jako 
$$E(X) = \sum_{\x in Im(X)} x \cdot P(X = x)$$
$$E(X) = \sum_{\omega \in \Omega} X(\omega) P(\{\omega\}$$

Navíc platí, že:

* $E(X + Y) = E(X) + E(Y)$
* $E(aX + b) = a E(X) + b$
* $E(XY) = E(X)E(Y)$ pokud $X,Y$ jsou nezávislé

**DEF** Rozptyl: $var(X) = E((X - E(X))^2)$.

**DEF** směrodatná odchylka: $\sigma_X = \sqrt{var(X)}$


