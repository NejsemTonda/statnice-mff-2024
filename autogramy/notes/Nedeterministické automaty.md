# Nedeterministické automaty

**DEF** NDFA je definován jako uspořádaná pětice $(Q, \sum, \delta, q_0, F)$

* Q: množina všech stavů
* $\sum$: abeceda
* $\delta$: přechodová funkce $Q \times \sum \rightarrow 2^Q$
* $q_0 \subset Q$: počáteční stav
* $F \subset Q$: množina přijímaných vrcholů


Rozdíl je v tom, že nemáme jenom jeden současný stav ale množinu stavů. Musíme předefinovat přechodovou funkci (sjednocení všech cilových množin) 

Slovo $\alpha$ je přijímáno automatem $A$ právě když $\delta^*(\alpha) \cap F \not = \emptyset$

**THM** Pro každý regulární jazyk L(A) přijímaný nedeterministickým automatek A existuje deterministický automa A' takový, že $L(A) = L(A')$ 

**DK** Sestrojíme automat, s $2^Q$ stavy.
