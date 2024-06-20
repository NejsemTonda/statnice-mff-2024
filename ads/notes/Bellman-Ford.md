# Bellman-Ford

V podstatě to samé jako dijkstra, ale vrcholy dává do fronty

**THM** Bellamanův-fordův algoritmus spočítá vzdáleností $d(u, _)$ v čase $O(mn)$
**DK** převodem na různé fáze. V jedné fázi zavíráme jeden vrchol a otevíráme všechny jeho sousedy. Takových fází můžeme mít maximálně $n$ a v každé do fronty přidat maximálně $m$ vrcholů
