# Složitostní třídy

**DEF** Rozdhodovací problém: $L:\{0,1\}^* \rightarrow \{0,1\}$ 

### Převoditelnost
A je převoditelný na B, právě když
$$\exists f: \{0,1\} \rightarrow \{0,1\}^*$$
$$ \forall \alpha \in \{0,1\}^* A(\alpha) = B(f(\alpha))$$

a $f$ lze spočítat v polynomiálním čase

### Třída P

Pokud je problém L v třídě P, tak $\exists A$ algoritmus a $\exists p$ polynom, takový že $\forall x$ vstup $A(x)$ doběhne v čase $p(x)$ a $A(x) = L(x)$

### Třída NP

Pokud je problém L v třídě NP, tak $\exists V \in P$ verifikátor, $\exists g$ polynom a $\forall x: V(x) = 1$. (Tzn $\exists y$ certyfikát, $|x| \leq g(|x|)$ a $V(x,y) = 1$)

### NP těžké problémy

L je NP-těžký právě když $\forall K \in NP: K \rightarrow L$

### NP-úplné problémy

L je NP-úplný, pokud je L NP-těžký a navíc $L \in NP$

### NP-úplné problémy

* Logické:
    * SAT
    * 3-SAT
* Grafové:
    * Nezávislá množina
    * Klika
    * k-obarvitelnost
    * Hamiltonovská kružnice
    * 3D - párování
* číselné
    * součet podmožiny
    * Batoh
    * 2 loupežníci
    * 0,1 linerání rovnice
