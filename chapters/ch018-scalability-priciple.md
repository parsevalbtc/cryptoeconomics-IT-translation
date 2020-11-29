# Principio di Scalabilità



La [scalabilità]() è l'incremento proporzionale in alcuni aspetti della prestazione quando viene impiegato più hardware. Il _throughput_ di una [transazione]() bitcoin è perfettamente non scalabile in quanto nessun quantitativo di hardware aggiuntivo può incrementarla.

La [regola di consenso]() relativa limite alla dimensione di un [blocco]() stabilisce un compromesso arbitrario tra l'[utilità]() e la sicurezza del sistema. Un aumento della dimensione del blocco incrementa marginalmente il _throughput_ di [transazione]() e di conseguenza incrementa il costo di risorsa nella [validazione]() di transazione (i.e. elaborazione, storage, e banda). All'aumentare del costo di validazione, la sicurezza [economica]() è influenzata negativamente da un incrementato [rischio di centralizzazione](). Poiché il compromesso è arbitrario per natura, non vi è una dimensione ideale (del blocco).

Per ogni dimensione di blocco scelta il sistema rimane non scalabile a causa della necessità di avere la finalità nella [conferma]() (delle transazioni). Un insieme finito di transazioni deve essere selezionato, il che implica che altre potrebbero essere escluse. Questa esclusione è motivata a livello finanziario dal [costo-opportunità]() di non utilizzare il capitale sviluppato per il [mining](), e rappresenta la manifestazione della non scalabilità. Questa scarsità intrinseca necessita di un [mercato]() competitivo per le conferme, e che si finanzia in proporzione alla domanda per la moneta.

L'effettiva capacità si supportare transazioni aggiuntive, e di conseguenza l'utilità, può essere incrementata dal [_layering_](). Questo rappresenta un compromesso di sicurezza di tipo _locale_ e _limitato nel tempo_, in contrasto al compromesso di sicurezza di tipo _sistemico_ e _persistente_ che caratterizza l'aumento della dimensione del blocco.  Entrambi i compromessi abbassano ma non elimina la [soglia di utilità](), che implica che la [proprietà di stabilità]() è conservata.

**Pertanto la stabilità e la non scalabilità esistono per ogni dimensione del blocco e per ogni livello di layering.**



