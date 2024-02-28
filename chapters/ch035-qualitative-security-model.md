# Modello di Sicurezza Qualitativo



##### Modello di Decentralizzazione

Nel [Principio del Social Network](ch024-social-network-principle.md) è stato mostrato come Bitcoin sia una rete di relazioni [umane](ch101-glossary.md#persona). Questa rete può essere modellizzata come un [grafo diretto](https://it.wikipedia.org/wiki/Grafo) dove ogni vertice rappresenta un [commerciante](ch101-glossary.md#commerciante) e ogni lato rappresenta uno [scambio](ch101-glossary.md#scambio) che coinvolge bitcoin. I lati indicano la direzione verso cui si muove la [moneta](ch101-glossary.md#moneta) e ne viene data quantificazione attraverso il numero di [unità](ch101-glossary.md#unità) scambiate. Si presume che tutti i [proprietari](ch101-glossary.md#proprietario) siano stati commercianti quando la moneta è stata ricevuta, anche in qualità di [miner](ch101-glossary.md#miner) (che vendono [conferme](ch101-glossary.md#conferma)) e come percettori di beneficenza (che vendono [valore intangibile](https://it.wikipedia.org/wiki/Avviamento_d%27azienda)).

Se una persona non accetta personalmente la moneta, o non [valida](ch101-glossary.md#validazione) di persona la moneta accettata, questa persona non può rigettare le moneta invalida (n.d.t. falsa). La persona in questione sta affidando questo compito ad una autorità [centralizzata](ch101-glossary.md#centralizzazione). **Tutte le persone che usano la stessa entità delegata vengono ridotte al solo vertice che la rappresenta.**

Per ciascun periodo di tempo, la sicurezza [economica](ch101-glossary.md#economia) è funzione del numero dei commercianti e della somiglianza degli importi transati. L'economia più forte verrebbe ottenuta se tutte le persone del mondo si scambiassero lo stesso quantitativo di unità in un determinato periodo, una situazione ideale che può essere chiamata un'economia "distribuita" (o completamente decentralizzata). L'economia più debole si avrebbe se una sola entità delegata accettasse tutte le unità in scambio in un determinato periodo, che risulterebbe essere un'economia "centralizzata". 

Più specificamente, il sistema più decentralizzato economicamente è quello che ha il maggior numero di vertici (i commercianti) con il più basso coefficiente di [variazione](https://it.wikipedia.org/wiki/Coefficiente_di_variazione) relativo ai lati in arrivo (i pagamenti). Definendo una funzione di distribuzione come l'inverso del coefficiente di variazione otteniamo:

```
decentralizzazione-economica = distribuzione(pagamenti) * commercianti
```

In maniera simile alla sicurezza economica, la sicurezza delle conferme può essere modellizzata come un [grafo nullo](https://it.wikipedia.org/wiki/Grafo_nullo). Ciascun [miner](ch101-glossary.md#miner) è rappresentato da un vertice sul grafo. Un [operatore di un dispositivo di mining](ch101-glossary.md#operatore-di-dispositivo-di-mining-grinder) non è un miner in quanto egli non ha capacità di scelta e solamente il miner può essere quindi rappresentato. L'[_hash power_](ch101-glossary.md#hash-power) totale impiegato da un miner costituisce il peso del vertice.

In ogni periodo di tempo la sicurezza delle conferme è funzione del numero di miner e della somiglianza dell'_hash power_ che essi controllano. La più elevata resistenza alla censura verrebbe ottenuta se tutte le persone nel mondo minassero con lo stesso _hash power_ in un dato periodo di tempo, una situazione ideale che può essere chiamata sistema di conferma "distribuito" (o completamente decentralizzato). Il sistema più debole sarebbe quello nel quale un solo miner controllasse il 100% dell'hash power che equivarrebbe ad un sistema "centralizzato" di conferma.

Più specificamente, il sistema più decentralizzato nella conferma è quello avente il maggior numero di vertici (miner) con la più alta distribuzione in peso (hash power):

```
decentralizzazione-nella-conferma = distribuzione(hash-power) * miner
```



##### Modello di Sicurezza

La sola [decentralizzazione](ch101-glossary.md#decentralizzazione) non è sinonimo di sicurezza. La sicurezza è il prodotto dell'attività, della distribuzione di tale attività e della frazione di umanità che vi partecipa.

```
sicurezza = attività * distribuzione * partecipazione
```

Poiché non vi è limite al numero di esseri umani, al numero di scambi o al livello di computazione, il livello di sicurezza è illimitato in ciascun asse. La sicurezza è illimitata anche con una distribuzione perfetta (i.e. infinita decentralizzazione). Un livello minimo pari a zero viene raggiunto sia con una partecipazione nulla che con un’attività nulla. La sicurezza economica e della conferma possono essere quindi definite come:
```
sicurezza-economica = pagamenti * distribuzione(pagamenti) * [commercianti / umanità]
sicurezza-nella-conferma = hash-power * distribuzione(hash-power) * [miner / umanità]
```

##### Limiti del Modello

Queste relazioni non dicono nulla sulla assoluta efficacia rappresentata da ciascun valore, o sull'efficacia relativa di ciascuna coppia di valori, tranne per il fatto che un valore maggiore rappresenta una maggiore efficacia. Ciò non è dovuto ad una carenza nel modello. I fattori includono le persone, e in maniera specifica l'efficacia della loro abilità individuale a [resistere](ch004-axiom-of-resistance.md) e la loro percezione del [valore](ch101-glossary.md#valore) nella moneta. Tutti coloro che validano o che minano offrono un certo livello di resistenza ma non vi è sottintesa continuità. Ci si riferisce infatti ad un "livello" di sicurezza e non ad un "quantitativo" di sicurezza.

Come mostrato ne il [Principio dei Dati Pubblici](ch023-public-data-principle.md), l'anonimità è uno strumento che aiuta a difendere la possibilità di ciascuno di commerciare e/o minare. Per questa ragione, il livello di decentralizzazione non può essere mai misurato; il modello rappresenta un aiuto a livello concettuale. Come mostrato nella [Fallacia del Bilanciamento del Potere](ch042-balance-of-power-fallacy.md), la sicurezza che viene dedicata da ciascuno dei due sottogruppi è complementare e indipendente da quella dell'altro. Nonostante le persone possono decidere di commerciare e/o minare indipendentemente in futuro, la [Fallacia dello Scarafaggio](ch045-cockroach-fallacy.md) mostra che essi non stanno contribuendo alla sicurezza finché non decidono di farlo (n.d.t. in maniera attiva). Questo modello è rappresentativo della sicurezza finché essa è presente in un certo periodo di tempo.

---

Titolo originale: [Qualitative Security Model](https://github.com/libbitcoin/libbitcoin-system/wiki/Qualitative-Security-Model)

[Indice](/README.md)

