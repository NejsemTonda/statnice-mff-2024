# Dijkstra

Zavedu si novou funkci $h$, která říká hodnoty vrcholu. $\forall v \in V: h(v) = \infty$. Pro vrchol, ze kterého začínáme $h(v) = 0$ a vrchol otevřeme. Dokud existuje otevřený vrchol

* Vybereme vrchol $v$, který je otevřený s minimální hodnotou $min(h(v))$
* Pro každý sousedící vrchol $s$ otevřeme a $h(s) = min(h(s), h(v) + h(sv)$
* vrchol $v$ zavřeme

**THM** Pokud se algoritmus z $u$ zastaví, pak $\forall v \in V$ platí:

* $v$ dosažitelný z $u$, právě když
* $v$ je uzavřený, právě když
* $h(v)$ je konečné

**DK** zpětnou cestou

**THM** Pokud se algoritmus zastaví, pak $\forall v \in V: h(v) = d(u,v)$ 
**DK** Logicky


S implementací haldy beží v čáse $O(m \cdot log(n) + n \cdot log(n) + n \cdot log(n))$ za insert, popmin, delete.
