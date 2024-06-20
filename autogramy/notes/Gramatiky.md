# Gramatiky

**DEF** Gramatika $G$ je uspořádaná čtveřice $G = (V,T,S,P)$ kde:

* $V$: množina všech neterminálů
* $T$: Množina všec terminálů
* $S$: Počáteční stav
* $P$: Konečná množina pravidel typu $\alpha \rightarrow \beta, \alpha, \beta \in V \cup T$ a $\alpha$ obsahuje alespoň jeden neterminál

**DEF** Slovo $\alpha$ se přepíše na slovo $\beta$ pokud existuje rozklad $\alpha = \gamma \lambda \pi$ a $\beta = \gamma \delta \pi$ a $\lambda \rightarrow \delta \in P$

**DEF** Slovo $\beta$ je derivací slova $\alpha$ když existuje posloupnout přepisových pravidel, které mě dostanou z $\alpha$ do $\beta$


**DEF** Slovo $\alpha \in T^*$ je generované gramatikou $G$, pokud $G \Rightarrow \alpha$. Takovým slovům říkám $L(G)$ 

**DEF** Gramatika je bezkontexová, pokud jsou všehna její pravidla pouze ve tvaru $X \rightarrow \alpha, X \in V$

