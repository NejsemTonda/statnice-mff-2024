# A*

do prohledávání zapojíme heuristiku.

**DEF** Heuristika je přípustná, když $h(s) \leq$ nejlevnější cesta do cíle

**DEF** Heuristika je monotóní, když $c(s_1, s_2) + h(s_2) \geq h(s_1)$

**THM** Monotóní heuristika je vždy přípustná

**DEF** Heuristika $h_1$ dominuje $h_2$, pokud je monotóní, přípustná a $h_1(s) \leq h_2(s)$
