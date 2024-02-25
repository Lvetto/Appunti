## Equazione di Poisson
Abbiamo visto che $\nabla\cdot\vec{E}=\frac{\rho}{\epsilon_0}$ ([[Divergenza e legge di Gauss in forma differenziale]]) e che $\vec{E}=-\nabla V$ ([[Lavoro, energia e campo elettrico]]). Combinando le due equazioni si ottiene: $$ \nabla\cdot\nabla V = \nabla^2 V = -\frac{\rho}{\epsilon_0} $$
che è nota come equazione di Poisson.

Notiamo che un qualsiasi potenziale ottenuto dalla formula del potenziale di una distribuzione generica di carica (vista in [[Lavoro, energia e campo elettrico]]) soddisfa l'equazione di Poisson. Questo fatto può essere facilmente mostrato con un calcolo esplicito.

## Equazione di Laplace
Nel vuoto (cioè in assenza di cariche) l'equazione di Poisson si riduce all'equazione di Laplace: $$ \nabla^2 V = 0 $$
le cui soluzioni sono dette armoniche sferiche.

L'equazione di Laplace in generale ammette infinite soluzioni, per determinare quella che risolve un particolare problema è necessario introdurre delle condizioni al contorno. Queste condizioni di solito sono di due tipi:
- condizioni di Dirichlet: $V$ sulle superfici dei conduttori, al limite all'infinito
- condizioni di Neumann: $\frac{\partial V}{\partial\vec{n}}$ (derivata normale) sulle superfici dei conduttori, al limite all'infinito
Introdotte queste condizioni, la soluzione $\exists!$.

## Metodo delle cariche immagine
Sia $V_1$ una soluzione dell'equazione di Poisson e $V_2$ dell'equazione di Laplace, allora $V=V_1+V_2$ risolve ancora l'equazione di Poisson (si mostra facilmente). 
Questo fatto ci permette di risolvere il generico problema di elettrostatica (con anche conduttori a potenziale noto) ricavando una soluzione generica dell'equazione di Poisson (che rispetti la distribuzione di cariche) e sommandola a una soluzione particolare dell'equazione di Laplace (che rispetti le condizioni al contorno). Si può mostrare che la soluzione così ottenuta esiste sempre ed è unica.

Questo metodo (o la sua controparte meno formale) è noto come metodo delle cariche immagine. Il processo descritto sopra può essere visto come la sostituzione delle condizioni al contorno (potenziale noto su una superficie) con una 'carica immagine' che ha lo stesso effetto. Solitamente viene usato nel calcolo dei campi elettrici.


#Elettrostatica