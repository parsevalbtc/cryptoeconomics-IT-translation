# Fallacia del Propagatore



La rete [_peer-to-peer_](ch101-glossary.md#peer-to-peer) del protocollo Bitcoin diffonde i [blocchi](ch101-glossary.md#blocco) e le [transazioni](ch101-glossary.md#transazione) [non confermate](ch101-glossary.md#non-confermata). Il [protocollo](ch101-glossary.md#protocollo) stesso permette ai [nodi](ch101-glossary.md#nodo) di proteggersi dagli attacchi di tipo [_denial of service_](ch101-glossary.md#denial-of-service). Di conseguenza, questo tipo di [comunicazione](ch101-glossary.md#comunicazione) non richiede l'uso dell'[identità](ch101-glossary.md#identità). Questo tipo di protezione è il modo con il quale la rete non richiede l'impiego di un permesso per parteciparvi.

Tuttavia, questa protezione si realizza ad un costo in termini di [latenza](ch101-glossary.md#latenza) degli [annunci](ch101-glossary.md#annuncio) e, a causa del [vantaggio di prossimità](ch036-proximity-premium-flaw.md), una più bassa latenza si traduce in un più elevato [_hash power_ apparente](ch101-glossary.md#hash-power-apparente). Di conseguenza i [miner](ch101-glossary.md#miner) competono per avere una più bassa latenza. Un modo per ridurre la latenza è tramite il [raggruppamento](ch101-glossary.md#raggruppamento-pooling), un altro è quello di utilizzare una rete di diffusione più efficiente. Presumibilmente, poiché il raggruppamento cede [potere](ch101-glossary.md#potere) all'operatore che fornisce tale servizio, la seconda opzione è preferibile.

Un modo per migliorare la diffusione è quello di _ottimizzare_ la rete _peer-to-peer_. L'altro è quello di unirsi ad un network distinto, chiamato [propagatore](ch101-glossary.md#propagatore-relay) (_relay_), che possiede una più bassa latenza dovuta alla rimozione delle protezioni degli attacchi _denial-of-service_, ad [esempio](http://bitcoinfibre.org):

> Il formato del messaggio cmpctblock è stato progettato per inserirsi efficacemente in un meccanismo di propagazione basato su UDP-FEC. La sola differenza è che il messaggio viene mandatato tramite UDP per mezzo del FEC... In questo modo, i collegamenti aggiuntivi non introducono maggiore latenza. Sfortunatamente, a causa della natura della nostra codifica del FEC, non è possibile sapere se pacchetti individuali fanno parte di un blocco legittimo, o di un vero e proprio blocco, e di conseguenza è possibile attivare questa ottimizzazione tra nodi che sono eseguiti dallo stesso gruppo.  >
> 
> *bitcoinfibre.org*

Il propagatore accetta una [comunicazione](ch101-glossary.md#comunicazione) da un insieme di miner per mezzo del protocollo _peer-to-peer_ o di altri protocolli. Il propagatore consiste di un insieme di [macchine](ch101-glossary.md#macchine) soggette al controllo del [relayer](ch101-glossary.md#relayer). Esso comunica gli annunci alla sua [rete interna](https://bitcoinmagazine.com/articles/blockstream-satellite-broadcasting-bitcoin-space) e infine ai miner che si sono uniti ad essa.

L'importante osservazione di sicurezza da analizzare è che la comunicazione per mezzo di un propagatore è soggetta al controllo del _relayer_. Poiché le protezioni dal _denial-of-service_ sono state rimosse il controllo di tipo centrale è _necessario_ per il funzionamento di questa configurazione. Il relayer può infatti ritardare certi blocchi sulla base del miner, della regione, di una specifica [segnalazione](ch101-glossary.md#segnalazione-signal), di un mancato pagamento etc. Un relayer vende una latenza ridotta e fa quindi parte del business del mining a tutti gli effetti. Dal punto di vista della sicurezza non importa che il servizio sia offerto gratuitamente. I miner potrebbero offrire gratuitamente agli [operatori dei dispositivi di mining](ch101-glossary.md#operatore-di-dispositivo-di-mining) (_grinder_) latenza e [varianza](ch101-glossary.md#varianza) ridotte.

I propagatori sono [aggregazioni](ch101-glossary.md#aggregazione) di miner e i miner sono a loro volta aggregazioni di _grinder_. Più grande è l'aggregazione di _hash power_ maggiore è il profitto del centro di mining, così come lo è del propagatore. Si può considerare che i _grinder_ siano liberi di lasciare i centri di mining e che i miner siano liberi di lasciare i propagatori, ed è possibile per un _grinder_ operare sul suo stesso centro di mining e sul suo stesso propagatore. Ma le aggregazioni più estese sono più profittevoli, cosicché abbandonare i più grandi propagatori o centri di mining [incrementa il costo relativo](ch032-zero-sum-property.md).

Una teoria sostiene che i propagatori riducano la pressione al raggruppamento. Si tratta di un errore. **Ogni riduzione al raggruppamento causata da un propagatore non scompare ma è trasferita al propagatore stesso come raggruppamento aggiuntivo**. Le statistiche dei propagatori non vengono mai affiancate alle statistiche del mining, mascherando questo trasferimento di potere tra i due aggregati. Questo può portare le persone a credere che il mining sia molto meno raggruppato di quanto non sia in realtà.

---

Titolo originale: [Relay Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Relay-Fallacy)

[Indice](/README.md)
