# PCA

Hledáme projekci do nižšího prostoru, která bude mít co nejnižší chybu. Tzn.

$$L = \frac{1}{N} \sum_i ||x_i - \hat{x_i}||$$

Chybu minimalizujeme tím, že uděláme projekci do ortonormální báze $(u_i, \dots u_j)$

$$z_{i,j} = x_i^T u_j, b_j = \hat{x}^T u_j$$

To znamená, že loss klíďo můžeme přpsat na

$$L = \frac{1}{N} \sum_{i=1}^M \sum_{i=M+1}^D (x_i - \hat{x})^T(x_i - \hat{x})^2 = \sum_{i=M+1}^D u_1^T S u_1$$

