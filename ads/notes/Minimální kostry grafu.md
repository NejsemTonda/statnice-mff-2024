# Minimální kostry grafu

Mějme váhovou funkci $w: E \rightarrow R$. $w(H) = \sum_{e \in h} w(e)$. Minimální kostra grafu je podgraf, který obsahuje všechny vrcholy a je strom a je minimální co do $h$.


### Jarníkův algoritmus

Náhodně vybereme jeden vrchol z V, tento vrchol patří do kostry T. Vybereme nejlehčí hranu z V\T a její vrchol přidáme do T. Opakujeme n-krát


**DEF** Elementární řez je množiná všechn hran mezi A a V\A

**LEMMA** Řezové lemma nejlehčí hrana z každého elementárního řezu je v každé kostře
**DK** Graf musí být spojitý, lepší vybrat tu nejlehčí hranu. Z obrázku to jde vidět.

**THM** Jarníkův algoritmus najde nejlehčí kostru 
**DK** Algoritmus vždy přidá tu nejlehčí hranu mezi kostrou a zbytkem grafu. Ta musí být v minimální kostře.

### Borůvkův algoritmus

Postupně pěstujeme stromečky.

**THM** Borůvkův algoritmus se zastaví po $log_2(n)$ iteracích a vydá minimální kostru
**DK** Víme, že po k iterací má každý strom lesa alespo $2^k$ vrcholů. To jde dokázat indukcí. Minimální kostru dostanme z řezového lemmatu.



