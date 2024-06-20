# Pravé Lineární gramatiky

**DEF** Gramatika je pravá lineární pokud jsou všechna její pravidla ve tvaru $X \rightarrow \alpha Y$ 

**THM** Každý regulání jazyk se dá vygenerovat pomocí RLG
**DK** Mejmě DFA, který takový jazyk generuje. Setrojíme gramatiku, kde:

* $V = Q$
* $S = q_0$
* $T = \sum$
* S pravidly:
    * $X \rightarrow aY$, kde $\delta(X, a) = Y)$
    * $X \rightarrow \epsilon$ pro každé $X \in T$

**THM** Každá RLG generuje regulární jazyk
**DK** Podobným způsobem vytvoříme $\lambda$-NDFA, který bude bude stejný jako gramatika.
