# Spojité

**DEF** Distribuční funkce $F_X: \Omega \to R$ je difinováná jako:
$$F_X(x) = P(X \leq x) = P(\{\omega \in \Omega : X(\omega) \leq x\}$$

* $F_X$ je neklesající 
* $\lim_{x \to -\infty} F_X(x) = 0$
* $\lim_{x \to \infty} F_X(x) = 1$
* $F_X$ je zprava spojitá

**DEF** Náhodnou veličinu nazýváme spojitou, pokud existuje $f$ taková, že
$$F_X(x) = \int_{-\infty}^x f(t) dt$$

**DEF** Střední hodnota spojité náhodné veličiny
$$E(X) = \int_{-\infty}^{\infty}x f(x) dx$$ 

**DEF** Spojitá normální distribuce má ditribuční funkci $f_X = \phi = \frac{1}{\sqrt{2\pi}} e^{-x^2/2}$. Hostotní fuknci značíme $\Phi$
