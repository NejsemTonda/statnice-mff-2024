# Věty

**THM** Bayeosva věta
$$P(A|B) = \frac{P(B|A) P(A)}{P(B)}$$

**THM** Markovova nerovnost:
$$P(X \geq \lambda) \leq \frac{E(X)}{\lambda}$$

**THM** Silný zákon velkých čísel: Nechť $X_1, X_2, \dots$ jsou stejné rozdělené nezávislé náhodné veličiny se střední hodnostou $\mu$ a rozptilem $\sigma^2$. Pak
$$\lim_{n \to \infty} \frac{(X_1 + X_2 + \dots)}{n} = \mu$$

**THM** Slabý zákon velkých čísel:Nechť $X_1, X_2, \dots$ jsou stejné rozdělené nezávislé náhodné veličiny se střední hodnostou $\mu$ a rozptilem $\sigma^2$. Pak pro nějake $\epsilon > 0$ platí, že:
$$\lim_{n \to \infty} P(|\frac{(X_1 + X_2 + \dots)}{n} - \mu| > \epsilon) = 0$$

**THM** Centrální limitní věta:Nechť $X_1, X_2, \dots$ jsou stejné rozdělené nezávislé náhodné veličiny se střední hodnostou $\mu$ a rozptilem $\sigma^2$. Označme 
$$Y_n = \frac{X_1 + X_2 + \dots - n \mu}{\sqrt{n} \sigma}$$.
Pak platí, že 
$$Y_n \to^d N(0, 1)$$
