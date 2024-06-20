# Ortogonalita

**DEF** Systém vektorů $V$ je ortogonální, právě když $\forall v_1, v_2 \in V, v_1 \not = v_2: <v_1, v_2> = 0$. Ortonormální jej nazvem, pokud $\forall v \in V: ||v|| = 1$ 

**THM** Fourieorvy koeficienty: Nechť $z_1, \dots, z_2$ je ortonormální báze $V$. Pak $\forall x \in V: x = \sum_i <x, z_i>z_i$ 


**DEF** Nechť vektorový prostor $V$ a $M \subset V$. Ortogonální doplněk množiny $M$ je $\{x \in V, \forall y \in M: <x,y> = 0\}$

**DEF** Buď $V$ vektorový prostor a $U \subset V$ podprostor. Pak ortonormánlní projekce $x \in V$ do prostory $U$ je takový vektor $y$ (občas $x_U$), že:
$$||x - y||= min_{y \in U} ||x-y||$$


**THM** Nechť $U$ je vektorový podprostor konečně generovaného vektorového podprostoru $V$. Pokud je $z_1, \dots, z_n$ otronormální báze $U$, pak jakékoliv $x \in V$ můžeme projektorvat do $U$:
$$x_U = \sum_i <x, z_i> z_i$$


