# Použití

### Problém šatnářky

Chceme spočítat, kolik existuje permutací bez pevného bodu

Nechť $A = \Bigcup_i A_i$ množina všech permutací s jedňím a více pevnými body. $A_i =$ množina všech permutací, kde je pevným bod na pozici $i$. $|A_i|$ je $(n-1)!$. $A_i$ ale může mít více pevných bodů a ty chceme vyřadit. Pro $i \not = j$ platí $|A_i \cap A_j| = (n-2)!$ atd.
$$|A| = \sum_{k=1}^n (-1)^{k+1} \sum_{I \in {\n choose k}} |\Bigcap_{i \in I} A_i|$$
$$|A| = \sum_{k=1}^n (-1)^{k+1} \sum_{I \in {\n choose k}} (n-k)!$$
$$|A| = \sum_{k=1}^n (-1)^{k+1} {\n choose k} (n-k)!$$
$$|A| = \sum_{k=1}^n (-1)^{k+1} \frac{n!}{k! (n-k)!} (n-k)!$$
$$|A| = n! \sum_{k=1}^n  \frac{(-1)^{k+1}}{k!}$$
$$|A| = \frac{n!}{1!} - \frac{n!}{2!} + \frac{n!}{3!} - \frac{n!}{4!} + \dots$$ 

Tzn. počet všech permutací bez pevného bodu je $n! - |A|$


### Počet Surjekcí

### Eulerova funkce
