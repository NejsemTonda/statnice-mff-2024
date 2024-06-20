# Kombinační čísla

**DEF** Kombinační číslo ${n \choose k}= \frac{n!}{k! (n-k)!}$ 

* ${n \choose k}= {n-k \choose k}$
* ${n -1 \choose k} = {n-1 \choose k} + {n -1 \choose k-1}$

**THM** Binomická věta:
    $$(a-b)^n = \sum_{i=0}^n {n \choose i} a^i b^{n-i}$$

**THM** Princip Inkluze a exkluze
$$|\bigcup_i A_i| = \sum_{k=1}^n (-1)^{k+1} \sum_{I \in {|n| \choose i}} |\bigcap_{i \in I} A_i|$$

**DK** Každý prvek započítáme právě jednou nalevo a naprava

* Nalevo jej započítáme právě jednou
* Napravo ho započítáme kolikrát?
    * Nechť $t =$ # započítání prvku
    * Pokud $t > k$, znamenáto, že aspoň v jedené množině $A_i$ už prvek není, tudíž za tyto součty 0krát
    * Pokud $t = k$ právě jednou
    * Pokud $t < k$ kolikrát si můžu z $k$ množin vybrat $t$-tici takový, že v nich je prvek? $t \choose k$.
    * Takže sčítáme $\sum_k (-1)^{k+1} {t \choose k}$, kombinatoricky $\to 1$



