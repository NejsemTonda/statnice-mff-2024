# plánování


Každá proměnná má navíc ještě časovou složku ($L_{x,y}^t$)

Přechodový model pak může vypadat následovně 
$$L_{x,y}^t \land \text{facingEast}^t \land \text{forward}^t \Rightarrow L_{x+1,y}^{t+1} \land \neq L_{x,y}^{t+1}$$

Model bude mít hodně proměnných, kromě toho, že řekneme, kde agent je, také musíme říct, kde agent není. To vede na hodně proměnných, což je nešťastné :(


