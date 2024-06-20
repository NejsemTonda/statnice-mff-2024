# Toky v sítích

**DEF** Síť je uspořádaná pětice $(V, E, z, s, c)$ kde:

* $(V, E) orientovaný graf$
* $c: E \rightarrow R^+$ je funcke, která udává kapacity
* $z, s \in V$ zdroj a stok

**DEF** Tok v síti je funkce $f: E \rightarrow R^+$, taková že

* $\forall e \in E: f(e) \leq c(e)$
* Kirchhoffův zákon: 

$$\sum_{u: uv \in E} f(uv) = \sum_{u:vu \in E} f(vu)$, kromě $z, s$$
