# Markovský model

Davá pravděpodobností distribuci přes současné stavi podmíněné všemi předchozími stavy $P(X_t | X_{t-1}, \dots X_0)$

Markovská podmínka specifikuje, že součásná distribuce záleží jenom na té předešlé
$$P(X_t | X_{t-1}, \dots X_0) = P(X_t | X_{t-1})$$

Pokud proměnné $X$ přímo nepozorujeme, ale máme k dispozici pozorvání $P(E_t | X_{0:t-1}, E_{1:t}) = P(E_t | X_t)$ (současné pozorování závisí pouze na současném stavu) jedná se o skrytý markovský model

**DEF** Filtrování: Úkol je zjistit, v jakém stavu jsem za daného pozorování $P(X_t | E_{1:t})$

**DEF** Predikce: Úkol je zjistit, v jakém stavu se možná budu v budoucnu nacházet $P(X_t | E_{1:t})$

**DEF** Vyhlazování: V jakých stavech jsem nejspíš byl v minulosti $P(X_k | E_{1:t})$ pro $0 \leq k \leq t$

**DEF** Vysvětlení: To samé jako vysvětlení ale nezískává distribuci přes stavi ale jenom nejpravděpodobnější cestu $argmax_{x_{1:t}} P(x_{1:t} | E_{1:t})$

### Dynamické Bayesovské sítě

???
