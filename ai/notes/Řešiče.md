# Řešiče

Pro binární CSP

### Backtracking

Jednoduché DFS, v každém kroce zkontrolujeme podmínky, pokud jsem nějakou porušili, vrátíme se zpátky

### AC-3

**DEF** Hrana z $V_i$ do $V_j$ konzistetní, pokud platí $\forall x \in D_i \exists y \in D_j: c(V_i=x, V_j=y)$ (c jakože correct, neporušuje žádnou podmínku) a zároveň $V_j, V_i$ je konzistentní

O CSP řekneme, že je že hranově konzistentní, pokud je každá jeho hrana konzistentní.

* Snažím se jenom zredukovat domény jednotlivých hran

1. dokud fronta není prázdná $(V_i, V_j) = pop(\text{fronta})$
2. Odstraním všechny nekonzistence mezi $(V_i, V_j)$
3. Pokud se mi nějaké podařilo odstranit, přidám všechny $(V_i, *)$ do fronty

* Odstranňování nekonzistentních hran

1. pro všechna $x \in D_i$, pokud neexistuje proměnná $y \in D_j$, která by splňovala podmínky, $x$ odstraním
2. return

* Vyberu libovolné proměnné

### MAC

Maintaining Arc Consistenci: Backtrack + AC

Velká myšlenka: Když přiřadím proměnnou, kouknu se na všechny její podmínky a odstraním takové proměnné, abych zachoval hranovou konzistenci

### Převod na nebinární CSP

vytvoříme bipartní graf, na jedné straně proměnné a na druhé jejich domény. Vytvoříme maximální párování. Z domén odstraníme ty přiřazení, které nejsou v maximálním párování.
