# Fallacia dell'Esaurimento dell'Energia



Esiste una teoria secondo la quale la [_proof_of_work_]() (PoW) potrebbe esaurire tutta l'energia disponibile per le perosone. La PoW converte l'energia in una barriera alla [doppia spesa]() [crescente monotonamente]() per ogni data [transazione](). Questo è confrontabile con l'energia spesa nel rendere sicura qualsiasi moneta dalla contraffazione (dal suo stesso ente emittente o in altra forma).

Lo scopo di ogni misura di sicurezza è quello di creare un costo necessario a superare tale misura; i.e. una barriera finanziaria. Bitcoin crea la sua barriera alla doppia spesa obbligando [l'attaccante]() a sostituire il [ramo]() della transazione bersaglio con un [ramo]() avente probabilisticamente maggior [lavoro]().  Curiosamente, questa sostituzione eleva ancora maggiormente la barriera per i successivi attaccanti. **L'energia spesa non è un fattore importante in forma indipendente dal processo, la barriera eretta è l'onere _finanziario_ che l'attaccante deve necessariamente affrontare**.

La barriera di sicurezza (S) di un [blocco]() è il prodotto del costo unitario di un [hash]() (C), dell'_[hash rate]()_ (H) e del periodo di tempo (T).

```
S = C * H * T
```

L'[aggiustamento]() porta alla variazione dell'[_hash rate_]() necessario per mantenere un periodo costante per un dato livello del costo di un hash e di sicurezza.

```
T = S / (C * H)
```

Un periodo costante implica che l'_hash rate_ è inversamente proporzionale al costo per una data sicurezza.

```
H ~ S / C
```

Quando l'approvvigionamento di energia viene ridotto il suo [prezzo]() deve aumentare, cosa che riduce il quantitativo speso per un dato livello di sicurezza. Di conseguenza l'energia non può essere esaurita dal [mining]() e la teoria è invalida.