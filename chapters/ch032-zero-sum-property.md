# Proprietà del Gioco a Somma Zero



Il [mining](ch101-glossary.md#centro-di-mining-mine) di Bitcoin è un [gioco a somma zero](https://it.wikipedia.org/wiki/Gioco_a_somma_zero). In media la [catena](ch101-glossary.md#catena) cresce di un [blocco](ch101-glossary.md#blocco) ogni 10 minuti, dove la totalità della [ricompensa](ch101-glossary.md#ricompensa-reward) viene controllata dal [miner](ch101-glossary.md#miner) che lo ha trovato. Tenendo da parte [la pressioni al raggruppamento (pooling)](ch039-pooling-pressure-risk.md), i miner competono per ottenere la ricompensa e ciascuno totalizzerà, in media, una ricompensa proporzionale al suo [_hash rate_](ch101-glossary.md#hash-rate). Per un miner la differenza tra il costo e la ricompensa nel tempo rappresenta il suo [interesse](ch101-glossary.md#interesse) sul capitale [investito](ch101-glossary.md#dare-in-prestito-investire) nel suo centro di mining.

Vi sono due aspetti da considerare nella proprietà del gioco a somma zero:

* Nell'intervallo di tempo compreso tra due [organizzazioni](ch101-glossary.md#organizzazione), un miner guadagna una ricompensa e tutti gli altri miner non ne guadagnano nessuna. Né il prezzo, né _l'hash rate_, né la [difficoltà](ch101-glossary.md#difficoltà), né l'[inflazione](ch101-glossary.md#inflazione), né le [commissioni](ch101-glossary.md#commissione-fee-di-transazione), o qualsiasi altro fattore ha alcun effetto su questa proprietà.
* L'entità della ricompensa, misurata in [unità](ch101-glossary.md#unità) della [moneta](ch101-glossary.md#moneta) (n.d.t. minata) o nel [prezzo](ch101-glossary.md#prezzo) di [scambio](ch101-glossary.md#scambio-di-unità), non ha effetto sul tasso di rendimento del capitale.

Visto in maniera idealizzata il mining di Bitcoin è un [sistema chiuso](https://en.wikipedia.org/wiki/Closed_system). Il ritorno sul capitale varia relativamente ad altri centri di mining ed è dovuto ai difetti del protocollo quali il [premio di prossimità](ch036-proximity-premium-flaw.md)  e lo [sconto di varianza](ch037-variance-discount-flaw.md), così come alle [economie di scala](https://it.wikipedia.org/wiki/Economie_di_scala) e all'efficienza degli operatori. **Tuttavia, poiché questi fattori impattano sul costo relativo dell'hash power, è la proporzionalità dei tassi di rendimento ad essere influenzata, non il rendimento globale.**

Il Bitcoin nella realtà non è un sistema chiuso. Le pressioni all'aggregazione a [mercato](ch101-glossary.md#mercato) e anti-mercato dovute rispettivamente alla [variazione](ch101-glossary.md#variazione) e alla [distorsione](ch101-glossary.md#distorsione) sono di tipo esterno. A livello fondamentale, Bitcoin esiste per difendere i mercati mettendo necessariamente in conflitto la distorsione con la variazione (o con la sua mancanza).

Quando la distorsione è applicata ad un miner in questo sistema a somma zero, tutti gli altri miner ne sono affetti. Per esempio, un [sussidio](https://it.wikipedia.org/wiki/Sussidio) (da non confondersi con la componente di [sussidio](ch101-glossary.md#sussidio-subsidy) prevista dal [consenso](ch101-glossary.md#consenso)) dato ad un miner agisce come una tassa su tutti gli altri e, viceversa, una tassa su un miner agisce come un sussidio su tutti gli altri. Il miner sussidiato opera ad un costo più basso per lo stesso [hash rate](ch101-glossary.md#hash-rate), oppure ha un maggiore _hash rate_ effettivo (i.e. l'[_hash power_](ch101-glossary.md#hash-power)) per lo stesso costo. Il miner tassato opera ad un costo più elevato per lo stesso _hash rate_, oppure possiede un _hash rate_ più basso allo stesso costo.

Un'entità che eroga sussidi non si attende alcun ritorno sul capitale, altrimenti esso/essa sarebbe considerata un investitore. L'investimento è una forza di mercato attraverso la quale un miner paga un prezzo di mercato per il capitale. Con un tasso di rendimento effettivo più elevato il miner sussidiato attrae più capitale degli altri miner, continuando ad espandere l'_hash power_ finché non rimane il solo [miner](ch101-glossary.md#miner) con la [maggioranza dell'_hash power_](ch101-glossary.md#maggioranza-dellhash-power). L'obiettivo dell'entità sussidiante è, in ultima istanza, quello di *controllare* il centro di mining sussidiato.

Una tassa sul mining ha l'effetto di muovere tutto l'_hash power_ verso i centri di mining non tassati, al di fuori della giurisdizione dell'autorità tassante, in quanto il capitale va alla ricerca di rendimenti a mercato. Se applicata in maniera estesa, questa tassa può portare il controllo dell'autorità sulle sue stesse operazioni di mining. In altre parole, l'autorità può sopprimere la competizione. Questo obiettivo può essere raggiunto anche attraverso una tassa del 100% per la quale l'autorità [coopta](ch101-glossary.md#cooptazione-co-option) i centri di mining. L'effetto è lo stesso, il centro di mining tassato viene fatto fallire e i ricavi della tassa vengono utilizzati per le attività di controllo. 

Le conseguenze del gioco a somma zero nel mining combinate con l'intrinseca pressione al raggruppamento vengono approfondite nel [Paradosso del Livello di Minaccia](ch033-threat-level-paradox.md).

---

Titolo originale: [Zero Sum Property](https://github.com/libbitcoin/libbitcoin-system/wiki/Zero-Sum-Property)

[Indice](/README.md)
