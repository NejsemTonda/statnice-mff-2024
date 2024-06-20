# BVS

**DEF** Strom je binární, pokud je zakořeněný a každý jeho vrchol má nejvýše dva syny, u nichž rozlišujeme pravého a levého

**DEF** Binární vyhledávací strom je binární strom, jehož každému vrcholu přiřadíme unikátní klíč z univerza a pro každý vrchol platí, že
    $$\forall v \in V \forall a in L(v): k(a) < k(v)$$
    $$\forall v \in V \forall a in P(v): k(a) > k(v)$$

**DEF** BVS je dokonale vyvážený
    $$\forall v \in V: |L(v)| - |P(v)| \leq 1$$


**THM** Pro jakoukoliv implementaci INSERT a DELETE musí mít alespoň jedna z nich $\Omega(n)$. 
**DK** Vytvořím strom s $2^k-1$ vrcholy. Ten je jednoznačně určený. INSERT(n+1), DELETE(1). Strom má vrcholy 2..n+1 a stále je jednoznačně určený. Všechny listy se museli změnit. 
