# Fallacia del Blocco Vuoto



Esiste una teoria secondo la quale [minare](ch101-glossary.md#centro-di-mining-mine) [blocchi](ch101-glossary.md#blocco) vuoti rappresenti un [attacco](ch101-glossary.md#attacco). Tra le ipotesi, la teoria non richiede che i blocchi siano minati su un [ramo debole](ch101-glossary.md#ramo-debole-weak-branch) nel tentativo di permettere la [doppia spesa](ch101-glossary.md#doppia-spesa) e non specifica quale [persona](ch101-glossary.md#persona) venga attaccata.

Si prendano in considerazione i seguenti punti:

* Il termine "attacco" implica il furto. Il [_whitepaper_ di Bitcoin](https://bitcoin.org/bitcoin.pdf), ad esempio, utilizza il termine solamente per descrivere i tentativi di doppia spesa.
* Una [ricompensa](ch101-glossary.md#ricompensa-reward) di un blocco è costituita dalle [commissioni](ch101-glossary.md#commissioni-di-transazione-fee) per le [transazioni](ch101-glossary.md#transazione) e da un [sussidio](ch101-glossary.md#sussidio-subsidy) per il blocco. Il [miner](ch101-glossary.md#miner) che rinuncia alle commissioni delle transazioni non includendole in un blocco non è remunerato da esse.
* L'[_hash power_](ch101-glossary.md#hash-power) del miner contribuisce in maniera proporzionale alla sicurezza del network. Il sussidio rappresenta la compensazione per la sicurezza durante la fase [inflazionaria](ch101-glossary.md#inflazione). Lo scopo dell'inflazione è quello di distribuire razionalmente le [unità](ch101-glossary.md#unità). La distribuzione razionale è [scambiata](ch101-glossary.md#scambio-di-unità) specificamente in cambio di _hash power_, non al fine di includere transazioni.
* La [conferma](ch101-glossary.md#conferma) di transazioni non è garantita. Le commissioni sono l'incentivo per la conferma. La mancanza di conferme implica in maniera obiettiva l'insufficienza delle commissioni.
* I blocchi vuoti sono totalmente compatibili con le [regole del consenso](ch101-glossary.md#regole-del-consenso) e non possono essere ragionevolmente impediti da una nuova [regola](ch101-glossary.md#regola).

Inoltre, se il 10% dell'_hash power_ mina blocchi vuoti, le conferme richiederanno in media il 10% in più del tempo. Tuttavia, se un miner rimuove il 10% dell'_hash power_ totale, le conferme richiederanno sempre in media il 10% in più del tempo, fino al successivo [aggiustamento](ch101-glossary.md#aggiustamento) della [difficoltà](ch101-glossary.md#difficoltà). Minare un blocco vuoto è quindi indistinguibile dal non minare affatto.

Risulta utile investigare l'origine della fallacia. A causa della [Proprietà del Gioco a Somma Zero](ch032-zero-sum-property.md) si potrebbe teoricamente assumere che minare un blocco vuoto "slealmente" possa togliere la possibilità di confermare le transazioni.

Un miner impegna del capitale per minare, producendo, in ritorno, dell'_hash power_. Mettendo da parte gli [effetti del raggruppamento](ch039-pooling-pressure-risk.md), il miner viene sovvenzionato in proporzione all'_hash power_ prodotto. Senza questo [lavoro](ch101-glossary.md#lavoro) altri miner produrrebbero lo stesso numero medio di blocchi ad una [difficoltà](ch101-glossary.md#difficoltà) proporzionalmente minore. In altre parole, gli attacchi _reali_ sarebbero proporzionalmente meno costosi. Così, nonostante il miner non venga remunerato per includere transazioni, egli sta rendendo sicure le transazioni precedentemente confermate.

Poiché il [costo marginale](https://it.wikipedia.org/wiki/Costo_marginale) di includere una transazione è al di sotto dei livelli medi delle commissioni, il miner che mina un blocco vuoto sta subendo un [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0). Tale costo rappresenta il livello al quale il miner sta sussidiando la sicurezza della [catena](ch101-glossary.md#catena). Nonostante questo comportamento sembri economicamente irrazionale nel limitato contesto della moneta, esso può considerarsi razionale a causa del costo opportunità insito nell'aspettare a minare su un blocco [candidato](ch101-glossary.md#candidato) non vuoto in seguito ad un [annuncio](ch101-glossary.md#annuncio). **Nella misura in cui questa azione riduca i costi del miner, minare blocchi vuoti non può avere impatto né sulle commissioni né sul tasso di conferma.** La teoria è quindi invalida.

Nonostante un certo miner possa considerare vantaggioso minare blocchi vuoti, qualsiasi altra persona ha il [potere](ch101-glossary.md#potere) di fare altrimenti. È la facoltà di esercitare questa opportunità improntata alla competitività e al fine personale a rendere sicura la moneta nei confronti degli attacchi reali.

---

Titolo originale: [Empty Block Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Empty-Block-Fallacy)

[Indice](/README.md)



