# Logické řešiče

* CNF a DNF známe z logiky

### DPLL

Dostanu klauzule, list proměnných, model = {}

1. Pokud je každá klouzule *true*, vrátím *true*
2. Pokud je každá klouzule *false*, vrátím *false*
3. Pokud existuje Pure-Symobol, nastavím na true a zavolám DPLL
    * Pure-Symbol je takový, který je je všude se stejným znaménkem
4. Pokud existuje jednotková klazule nastavim na true a zavolám DPLL
    * Jednotková klauzle je taková, která v sobě má jenom jeden literál
5. Vezmu první nesplněný symbol a nastavím na true zkusím DPLL
6. Pokud se nepodařilo nastavím na false a zkusíĺ DPLL
7. Vrátím false

### Dopředné a zpětné řetězení

**DEF** Hornerova klauzule je taková klauzule, že obsahuje nevjýše jeden pozitvní literál tzn $a \land (a \lor \neg b) \land (b \lor \neg a \lor \neg c)$

Můžeme přepsat na implikace $a \land (b \Rightarrow a) \land (c \land a \Rightarrow b)$.

Nastavíme DAG s proměnými. Každá hrana odpovídá jedně implikaci. Proměnné si drží hodnotu kolik jejich přepodpokladů musí být ještě splněno. Pokud je 0, proměnnou nastavíme jako splněnou. Pokaždé, když splníme proměnnou snížíme počítadlo všem proměnným co mě měli jako předpoklad. Nastavíme data na splněno (forward chaining)


Obráceně nastavíme cíl na splněno a následně splníme všechny jeho přepoklady a pak přepoklady předpokladů atd...
