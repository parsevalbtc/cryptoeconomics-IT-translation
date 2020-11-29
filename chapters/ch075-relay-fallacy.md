# Fallacia della Propagazione



La rete [_peer-to-peer_]() [del protocollo Bitcoin] diffonde i [blocchi]() e le [transazioni]() [non confermate](). Il [protocollo]() stesso permette ai nodi di proteggersi dagli attacchi di tipo [_denial of service_](). Conseguentemente questo tipo di [comunicazione]() non richiede l'uso di [identità](). Questo tipo di protezione è il modo in cui la rete permette di evitare l'uso di un permesso a parteciparvi.

Tuttavia questa protezione si realizza ad un costo in termini di [latenza]() degli [annunci](), e a causa del [vantaggio di prossimità]() una più bassa latenza si manifesta come un più elevato livello [apparente di _hash power_](). Di conseguenza i miner competono per avere una più bassa latenza. Un modo per ridurre la latenza è tramite il [raggruppamento]() (pooling), un altro è quello di utilizzare una rete di diffusione più efficiente. Poiché il raggruppamento cede [potere]() all'operatore, probabilmente la seconda opzione è preferibile.

Un modo per migliorare la diffusione è quello di [ottimizzare]() la rete _peer-to-peer_. L'altro è quello di unirsi ad un network distinto, chiamato [propagatore]() (_relay_), che possiede una più bassa latenza dovuta alla rimozione delle protezioni degli attacchi _denial-of-service_, ad esempio:

> Il formato del messaggio cmpctblock è stato progettato per inserirsi in efficacemente in un meccanismo di propagazione basato su UDP-FEC. La sola differenza è che lo mandiamo tramite UDP per mezzo del FEC... In questo modo, dei collegamenti extra non introducono maggiore latenza. Sfortunatamente, a causa della natura di codifica del FEC, non possiamo sapere se pacchetti individuali fanno parte di un blocco leggittimo, o di un vero e proprio blocco, e di conseguenza è possibile attivare questa ottimizzazione tra nodi che sono eseguiti dallo stesso gruppo.  [bitcoinfibre.org](http://bitcoinfibre.org).

Il propagatore accetta una [comunicazione]()  da un insieme di miner, per mezzo del protocollo peer-to-peer o di altri protocolli. Il propagatore consiste di un insieme di [macchine]() soggette al controllo del [relayer](). Esso comunica gli annunci all'interno della sua [rete interna]() e ai infine ai miner che si sono uniti.

L'importante osservazione di sicurezza da fare è che la comunicazione per mezzo di un propagatore è soggetta la controllo del _relayer_. Poiché le protezioni dal _denial-of-service_ sono state rimosse il _controllo di tipo centrale_ è necessario per il funzionamento di questa configurazione. Il relayer può infatti ritardare certi blocchi sulla base del miner, della regione, di uno specifico [segnale](), mancato pagamento etc. Un relayer **vende una riduzione di latenza**, e fa quindi parte dell'attività del mining. Dal punto di vista della sicurezza non importa che il servizio sia offerto gratuitamente. I miner potrebbero offrire gratuitamente agli operatori dei dispositivi di mining ( ([grinder]()) latenza e [varianza]() ridotte.

I propagatori sono aggregazioni di miner e i miner sono a loro volta aggregazioni di grinder. Più grande è l'aggregazione di _hash power_ maggiore è il profitto del centro di mining, così come lo è del propagatore. Si può considerare che i grinder siano liberi di lasciare i centri di mining e che i miner siano liberi di lasciare i propagatori, ed è possibile per un grinder operare il suo stesso centro di mining e il suo stesso propagatore. Ma le aggregazioni più estese sono più profittevoli, così lasciare i più grandi propagatori o centri di mining incrementa il [costo relativo]().

Una teoria sostiene che i propagatori riducano la pressione al raggruppamento. Si tratta di una fallacia in quanto **ogni riduzione al raggruppamento causata da un propagatore non scompare ma è _trasferita_ al propagatore stesso come raggruppamento aggiuntivo**. Le statistiche del propagatore non sono mai mostrate affianco alle statistiche del mining, mascherando questo trasferimento di potere tra i due strumenti. Questo porta le persone a credere che il mining sia meno fortemente raggruppato di quanto non sia in realtà. La conseguenza di ciò è la noncuranza riguardo all'insicurezza causata dal reale livello di raggruppamento del mining.



