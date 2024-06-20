# Cholského rozklad

**THM** Pro každkou positivně definitní matici $A \in R^{n \times n}$ existuje právě jedna dolní trojuuhelníková matice $L \in R^{n \times n}$ s kladnou diagonálou, že $A = LL^T$


Cholského rozklad není těžké najít. Jde to velmi rychle $O(n^3)$. Můžeme si ušitřit nějaký čas třeba při hledání řešení rovnice $Ax = b$. Nejdřív najdeme řežení $Ly = b$ a pak $L^Tx = y$. 

Dále platí, že operace je skalárním součinem, právě když $<x, y>$ lze vyjádřit jako $<x,y> = x^TAy$ pro nějakou pozitivně semidefinitní matici $A$.



