La forza di Coulomb vale:
$$  F_i^j=\frac{1}{4\pi\epsilon_0}\frac{q_iq_j}{|r_{ij}|^3}r_{ij} $$
## Lavoro ed energia
Questa forza è conservativa, il lavoro compiuto per spostare una carica in un campo elettrico non dipende, dunque, dal percorso scelto. Il lavoro per spostare una carica da A a B vale:
$$ W = \int_A^B-F\cdot ds = \frac{q_1q_2}{4\pi\epsilon_0}\left(\frac{1}{B}-\frac{1}{A} \right) $$
L'energia elettrostatica è quindi definita come il lavoro compiuto per assemblare un sistema (portando le cariche dall'infinito).

## Campo elettrico
La forza di Coulomb dipende linearmente dalla carica in esame, definiamo quindi un campo vettoriale E: $$ \vec{E}=\lim\frac{\vec{F}}{q} $$
che equivale alla forza per unità di carica, misurato con una carica sufficientemente piccola da non modificare il sistema.

Il campo elettrico è locale, nel calcolo della forza conta solamente il suo valore in un punto e non come è stato generato.

Le linee di campo di E sono:
- tangenti ad E in ogni punto
- uscenti dalle cariche + e entranti nelle cariche -
- non incrociate
- hanno densità proporzionale al modulo di E

Per una distribuzione generica di carica $\rho$ vale: 
$$ E(r) = \frac{q}{4\pi\epsilon_0}\int_{R^3}\frac{\rho}{|r|^3}dV $$ 
Una carica puntiforme in posizione $\vec{r_0}$ è equivalente alla distribuzione:
 $$ \rho = \delta(\vec{r}-\vec{r_0})q $$
## Potenziale
Definiamo potenziale elettrico l'energia elettrostatica per unità di carica:
$$ V = \frac{U}{q} $$
Vale ovviamente $F=-\nabla V$ , da cui:
$$ E = -\nabla V $$
più formalmente:
$$ dV = E\cdot dr = \frac{\partial V}{\partial x}x + \frac{\partial V}{\partial y}y + \frac{\partial V}{\partial z}z = \nabla V\cdot dr  $$
Le superfici equipotenziali (cioè $V=const$) sono sempre perpendicolari alle linee di campo.


#Elettrostatica