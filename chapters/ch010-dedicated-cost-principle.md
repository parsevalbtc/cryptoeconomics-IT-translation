# Principio del Costo Dedicato



I costi non necessari che vengono sostenuti dai [miner](ch101-glossary.md#miner) non contribuiscono in alcun modo né alla resistenza alla [doppia spesa](ch101-glossary.md#doppia-spesa) né alla [resistenza alla censura](ch028-censorship-resistance-property). Questi costi costituiscono un vero spreco poiché rappresentano niente più che una misura dell'inefficienza del miner. Ad esempio, se un miner con [macchine](ch101-glossary.md#macchina) mal configurate spende una grande quantità di energia senza essere in grado di vincere la [ricompensa](ch101-glossary.md#ricompensa-reward) a causa della cattiva configurazione, ciò non dà alcun contributo alla sicurezza. Ogni costo che non è strettamente richiesto per la generazione ottimale di [hash power](ch101-glossary.md#hash-power) non è un costo necessario. La cattiva configurazione di un miner non rappresenta un costo per un altro miner.

E' stata formulata una teoria secondo la quale la [proof-of-work](ch101-glossary.md#prova) (PoW) possa essere resa più efficiente energeticamente introducendo costi non dedicati alla funzione di mining. Un esempio di questa teoria è l'impiego di capacità computazionale per la scoperta di [numeri primi](http://primecoin.io/). La ragione per incorporare questi costi deriva dal fatto che i risultati da essi prodotti hanno un presunto valore di mercato. In caso contrario, non ci sarebbe alcun valore nell'aggiungere un'ulteriore funzione.

Facendo un'analogia, i produttori di birra possono vendere i sottoprodotti di scarto dei cereali agli agricoltori. Questo migliora la loro efficienza eliminando un costo non necessario. In questo modo, nella misura in cui il sottoprodotto ha valore, la sua produzione non incorre in un costo netto. Ciònonostante i costi netti necessari devono salire al livello della ricompensa a causa della competizione. Quindi lo stesso risultato sarebbe raggiunto da una semplice PoW che consumi l'intero valore della ricompensa in aggiunta a dei processi energivori indipendenti che generino gli altri prodotti commercializzabili. **Ogni costo dedicato alla produzione di un valore vendibile indipendentemente può essere compensato attraverso la vendita di quel sottoprodotto**. Per questa ragione la teoria è invalida.

Il [_merged mining_](https://eprint.iacr.org/2017/791.pdf) viene solitamente implementato per risolvere il problema di avviare (_bootstrap_) una nuova moneta superando le fasi vulnerabili di basso [hash rate](ch101-glossary.md#hash-rate). Questo tipo di architettura non riconosce che l'_hash rate_ che non viene dedicato alla nuova [moneta](ch101-glossary.md#moneta) non contribuisce alla sua sicurezza. Poiché l'intero costo dell'_hash rate_ può essere recuperato vendendolo su una catena, non vi è alcun costo nel censurare le altre catene validate tramite _merged mining_.

---

Titolo originale: [Dedicated Cost Principle](https://github.com/libbitcoin/libbitcoin-system/wiki/Dedicated-Cost-Principle)

[Indice](/README.md)
