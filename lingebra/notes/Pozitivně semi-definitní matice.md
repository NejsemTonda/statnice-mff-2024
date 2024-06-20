# Pozitivně semi-definitní matice

**DEF** Buď $A \in R^{n \times n}$ symetrická matice. Pokud $x^TAx \leq 0$ pro všechna $x$, řekneme že je pozitivné semi-definitní. Pokud $>0$ tak positivné definitní.

Jeli $A$ positivně definitní, tak platí:

* Jeli $B$ pd, $A+B$ je pd
* $\alpha A$ je pd pro $\alpha >0$
* Jeli $A$ regulární, tak $A^{-1}$ je pd 
* Vlastní čísla $A$ jsou kladná
* Exitstuje matice $U \in R^{m \times n}$ hodnosti $n$, že $A = UU^T$

Jeli $A$ positivné semi-definitní:

* Vlastní čísla $A$ jsou nezáporná
* Exitstuje matice $U \in R^{m \times n}$ libovolné hodnosti, že $A = UU^T$


### Testování

$$A = \begin{matrix} \alpha && a^T \\ a && A^* \end{matrix}$$
$A$ je pd, pokud $\alpha > 0$ a $A^* - \frac{1}{\alpha}aa^T$ je pd

nebo

$A$ je pd, pod jsou determinanty všech hlavních podmatic kladné.

