# Rozděl a panuj

### Násobení dlouhých čísel

$$X = A \cdot 10^{n/2} + B$$
$$Y = C \cdot 10^{n/2} + D$$
$$XY = AC \cdot 10^n + (AD + BC) \cdot 10^{n/2} + BD$$
$$(A+B)(C+D) = AC + AD + BC + BD$$
$$AD + BC = (A+B)(C+D) - AC - BD$$
$$XY = AC \cdot 10^n + ((A+B)(C+D) - AC - BD) \cdot 10^{n/2} + BD$$

Tzn $T(n) = 3 T(n/2) + \Theta(n)$ 

### Strassen
