# Lineární zobrazení

**DEF** Lineární zobrazení je taková funkce $f: U \rightarrow V$ pro kterou platí, že:

* $f(u + v) = f(u) + f(v)$
* $f(\alpha u) = \alpha f(u)$


**DEF** Buď $f: U \rightarrow V$ lineárni zobrazení:

* obraz $f(U) = \{f(v): x \in U\}$
* $Ker(f) = \{x \in U: f(u) = 0\}$

**THM** Buď $f: U \rightarrow V$ lineárni zobrazení, pak platí: 

* $f(U) je podprostorem V$
* $Ker(f) je podprostorem U$


**THM** Buď $f: U \rightarrow V$ lineárni zobrazení, pak následující tvrzení jsou ekvivalentní:

* $f$ je prosté
* $Ker(f) = 0$
* obraz libovolné lineráné nezavislé množiny je nezávislá množina


**DEF** Buď $f: U \rightarrow V$ lineárni zobrazení, $B_U = \{x_1 \dots x_n\}$ báze U, $B_V = \{y_1 \dots y_n\} báze V. Nechť $\sum_i a_{ij}y_i = f(x_j)$. Potom matice zobrazení $A$ je tvořena prvnky $a_{ij}$. Značíme $_{B_V}[f]_{B_U}$

Taková matice vždy existuje a je jednoznačná.

**DEF** zobrazení je isomorfní, pokud je surjektivní a na. Pokud mezi dvěma prostory existuje isomorfní zobrazení, tyto prostory jsou isomorfní.

* Jeli $f: U \rightarrow V$ isomorfismus, pak $f^{-1}: V \rightarrow U$ je také isomorfismus
* Jsou-li $f: U \rightarrow V$ a $g: V \rightarrow W$ isomorfismi, pak $f \circ g$ je isomorfismus
