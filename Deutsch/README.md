# Complessità di comunicazione
Il problema di Deutsh consiste in una *black box* che accetta un bit o qubit e restituisce un bit o qubit. Non si sa se la funzione *f(x)* implementata dalla balck box sia costante o meno e si deve determinarlo testando la funzione stessa.
Un algoritmo convenzionale richiede due chiamate alla funzione, mentre un algoritmo quantistico una sola.
Questo semplice esempio è una dimostrazione della efficienza quantistica per quel che rigurda la complessità di comunicazione.

Il circuito con *f(x)* non costante:

![non-costante](circuit(3).png)

Il circuito con *f(x)*  costante:

![non-costante](circuit(3).png)
## Codifica del problema
Il problema viene risolto qui usando un circuito quantistico. La progettazione del circuito equivale alla preparazione di un diagramma di flusso. L'approccio usato è quello della modellazione semiclassica per cui la funzione *f* deve essere mappata in un operatore unitario U<sub>f</sub> 
- convenzionale

*x* &rarr; *f(x)*
