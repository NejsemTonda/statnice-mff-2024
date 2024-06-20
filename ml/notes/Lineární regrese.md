# Lineární regrese

Model: $y(x) = x^T w + b$

Snažíme se minimalizovat chybu, kterou většinou píšeme jako:

$$\frac{1}{2} \sum_i (y(x; w) - t_i)^2$$

Při zobrazování chyby většiunou dělíme spíš $N$

Derivace chybové funkce je
$$\frac{\partial}{\partial w_j} \frac{1}{2} \sum_i (x_i^T w -t_i)^2 = \frac{1}{2} \sum_i 2(x_i^T w -t_i) x_{ij}$$


### L2 regulrizace

změníme chybu na
$$\frac{1}{2} \sum_i (y(x; w) - t_i)^2 - \frac{\lambda}{2}||w||^2$$

Derivace je pak
$$w += w - \alpha \sum_{i \in b} \frac{1}{|b|} (x_i^Tw -t_i)x_i - \alpha \lambda w$$

