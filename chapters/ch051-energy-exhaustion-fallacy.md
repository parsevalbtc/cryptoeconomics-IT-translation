# Fallacia dell'Esaurimento dell'Energia



Esiste una teoria secondo la quale la [_proof_of_work_](ch101-glossary.md#prova) (PoW) potrebbe esaurire tutta l'energia disponibile per le persone. La PoW converte l'energia in una barriera contro la [doppia spesa](ch101-glossary.md#doppia-spesa) che [crescente monotonamente](https://it.wikipedia.org/wiki/Funzione_monotona) per ogni data [transazione](). Questo è confrontabile con l'energia spesa nel rendere sicura qualsiasi moneta dalla contraffazione (dal suo stesso ente emittente o in altra forma).

Lo scopo di ogni misura di sicurezza è quello di creare un costo necessario a superare tale misura; i.e. una barriera finanziaria. Bitcoin crea la sua barriera alla doppia spesa obbligando l'[attaccante](ch101-glossary.md#attacco) a sostituire il [ramo](ch101-glossary.md#ramo-branch) della transazione bersaglio con un ramo avente probabilisticamente maggior [lavoro](ch101-glossary.md#lavoro). Curiosamente, se la sostituzione ha successo la barriera per i successivi attaccanti viene elevata in misura ancora maggiore. **L'energia spesa non è un fattore importante indipendentemente dal processo, la barriera eretta è l'onere _finanziario_ che l'attaccante deve necessariamente affrontare**.

La barriera di sicurezza (S) di un [blocco](ch101-glossary.md#blocco) è il prodotto del costo unitario di un [hash](ch101-glossary.md#hash) (C), dell'_[hash rate](ch101-glossary.md#hash-rate)_ (H) e del periodo di tempo (T).

```
S = C * H * T
```

L'[aggiustamento](ch101-glossary.md#aggiustamento) porta alla variazione dell'[_hash rate_](ch101-glossary.md#) necessario per mantenere un periodo costante per un dato livello del costo di un hash e di sicurezza.

```
T = S / (C * H)
```

Un periodo costante implica che l'_hash rate_ è inversamente proporzionale al costo per un dato livello di sicurezza.

```
H ~ S / C
```

Quando l'approvvigionamento di energia viene ridotto il suo [prezzo](ch101-glossary.md#prezzo) deve aumentare, cosa che riduce il quantitativo speso per un dato livello di sicurezza. Di conseguenza l'energia non può essere esaurita dal [mining](ch101-glossary.md#centro-di-mining-mine) e la teoria è invalida.

---

Titolo originale: [Energy Exhaustion Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Energy-Exhaustion-Fallacy)

[Indice](/README.md)

