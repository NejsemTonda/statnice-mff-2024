# Kuchařkova věta

pro 

$$T(n) = a T(n/b) + \Theta(n^c), T(1) = 1$$

kde $a \geq 1, b > 1, c \geq 0$ platí, že:

$T(n) =$

* $\Theta(n^c log(n))$ pro $\frac{a}{b^c} =1$
* $\Theta(n^c)$ pro $\frac{a}{b^c} < 1$
* $\Theta(n^{log_b(a)})$ pro $\frac{a}{b^c} > 1$ 
