# Complessità di comunicazione
Il problema di Deutsch consiste in una *black box* che accetta un bit o qubit e restituisce un bit o qubit. Non si sa se la funzione *f(x)* implementata dalla balck box sia costante o meno e si deve determinarlo testando la funzione stessa.
Un algoritmo convenzionale richiede due chiamate alla funzione, mentre un algoritmo quantistico una sola.
Questo semplice esempio è una dimostrazione della efficienza quantistica per quel che rigurda la complessità di comunicazione.

Il circuito con *f(x)*  costante:

## Codifica del problema
Il problema viene risolto qui usando un circuito quantistico. La progettazione del circuito equivale alla preparazione di un diagramma di flusso. L'approccio usato è quello della modellazione semiclassica per cui la funzione *f* deve essere mappata in un operatore unitario U<sub>f</sub> 
- convenzionale
*x* &rarr; *f(x)*
- quantistica
*(x,y)*&rarr;*(x,y&oplus;f(x))*
- Funzione costante *f(1) == f(0) == 0 *
in questo caso si ricava che *U<sub>f</sub> = I&otimes;X*
Il circuito con *f(x)* non costante:

![non-costante](circuit(2).png)
- Funzione non costante *f(1) == 1, f(0) == 0 *
in questo caso si ricava che *U<sub>f</sub> = |0><0|&otimes;I+|1><1|&otimes;X*
Il circuito con *f(x)* non costante:

![non-costante](circuit(3).png)
