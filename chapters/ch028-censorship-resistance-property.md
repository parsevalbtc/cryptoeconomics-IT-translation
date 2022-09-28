# Proprietà di Resistenza alla Censura



La resistenza alla [censura](ch101-glossary.md#censura) è una conseguenza delle [commissioni](ch101-glossary.md#commissione-di-transazione-fee) di [transazione](ch101-glossary.md#transazione). L'applicazione della censura è di fatto indistinguibile dall'applicazione di un [_soft fork_](ch101-glossary.md#soft-fork), dove la [maggioranza dell'_hash power_](ch101-glossary.md#maggioranza-dellhash-power) rifiuta i [blocchi](ch101-glossary.md#blocco) che non applicano la censura. Senza questo tipo di azione le transazioni sono [confermate](ch101-glossary.md#conferma) su base economica razionale, a dispetto della soggettività individuale del singolo [miner](ch101-glossary.md#miner).

Un miner avente la maggioranza è finanziariamente profittevole. Per questa ragione non sopporta un costo nell'acquisire i mezzi per porre in atto la censura. Poiché il mining è necessariamente una attività [anonima](ch016-risk-sharing-principle.md), è sempre possibile per ogni potenziale soggetto acquisire e sviluppare la maggioranza dell'_hash power_ e controllarla ad ogni istante. Come mostrato nella [Fallacia della Proof of Work](ch073-proof-of-work-fallacy.md), gli [_hard fork_](ch101-glossary.md#hard-fork) non possono essere usati per sconfiggere selettivamente la forza censurante ma, al contrario, accelerano il collasso della [moneta](ch101-glossary.md#moneta).

Nel caso di una censura attiva, le commissioni delle transazioni che non vengono confermate possono essere aumentate. Questo premio sulle _fee_ va a creare un maggiore profitto potenziale per i miner che confermano le transazioni censurate. Se portata ad un livello sufficiente, questa opportunità produce una competizione addizionale e quindi un incremento complessivo di [_hash rate_](ch101-glossary.md#hash-rate).

Se il crescente [hash power](ch101-glossary.md#hash-power) di tipo non censurante eccede quello del censore, il controllo di quest'ultimo fallisce. Il censore si trova quindi di fronte alla scelta di sussidiare le operazioni o di abbandonarle. Solo lo [stato](ch101-glossary.md#stato) può sussidiare perpetuamente le operazioni in quanto può imporre la tassazione. Allo stesso tempo esso ottiene un guadagno dalla preservazione del suo stesso regime valutario. **Per mantenere il controllo della censura lo stato deve consumare un quantitativo di tasse almeno pari al livello del premio delle commissioni**.

Una moneta senza commissioni integrate ricadrebbe sotto il controllo di un censore o evolverebbe in un mercato parallelo delle commissioni. Come mostrato nella [Fallacia delle Commissioni a Parte](ch081-side-fee-fallacy.md) non è necessario che le commissioni siano integrate nel protocollo, tuttavia l'integrazione delle stesse rappresenta una importante tecnica di anonimizzazione. In ogni caso, la resistenza alla censura deriva unicamente dal premio sulle commissioni. La parte di [sussidio](ch101-glossary.md#sussidio-subsidy) della [ricompensa](ch101-glossary.md#ricompensa-reward) del blocco non contribuisce alla resistenza alla censura in quanto il censore guadagna lo stesso sussidio degli altri miner.

E' possibile che l'applicazione della censura posso portare ad un collasso del [prezzo](ch101-glossary.md#prezzo), causando una perdita alle operazioni del censore. Tuttavia, in questo caso, il suo obiettivo è stato raggiunto, non lasciando alcuna opportunità all'[economia](ch101-glossary.md#economia) di contrapporsi ad esso. Questo collasso può essere ottenuto ad un costo irrisorio semplicemente dimostrando l'intenzione di porre in essere la censura. E' anche possibile che un _soft fork_ creato per applicare la censura possa portare ad un *aumento* del prezzo, in quanto le attività del mercato legale si associano a tale misura applicata dallo stato. Cionondimeno, affinché la moneta sopravviva, la sua economia deve continuare a generare un premio in termini di commissioni sufficiente a sopraffare il censore.

Non può essere dimostrato che l'economia sia in grado di generare un livello di commissioni sufficiente a sopraffare il censore. In maniera simile, non può essere dimostrato che il censore sia disponibile e capace di sussidiare le proprie operazioni ad ogni livello. Non è quindi possibile dimostrare la resistenza alla censura. Questo è il motivo per cui la resistenza al controllo dello stato è [assiomatica](ch004-axiom-of-resistance.md).

---

Titolo originale: [Censorship Resistance Property](https://github.com/libbitcoin/libbitcoin-system/wiki/Censorship-Resistance-Property)

[Indice](/README.md)

