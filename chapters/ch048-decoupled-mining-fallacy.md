# Fallacia del Mining Disaccoppiato



Vi è una teoria secondo la quale la [sicurezza](ch035-qualitative-security-model.md) nel [mining](ch101-glossary.md#centro-di-mining-mine) [raggruppato](ch101-glossary.md#raggruppamento-pooling) (_pooling_) viene incrementata [disaccoppiando](ch101-glossary.md#disaccoppiamento-decouple) la [ricompensa](ch101-glossary.md#ricompensa-reward) dalla selezione delle transazione. La teoria ritiene che attraverso la condivisione della sola ricompensa, il controllo sulla selezione delle transazioni si sposti sui [miner](ch101-glossary.md#miner) con minore [_hash power_](ch101-glossary.md#hash-power). Questo implica una riduzione nello [sconto di varianza](ch037-variance-discount-flaw.md) e di conseguenza un incremento nella [competitività](ch014-other-means-principle.md) dei centri di mining più piccoli. Poiché i centri di mining più piccoli possono presumibilmente operare in maniera più coperta di quelle più grandi, questo a propria volta implicherebbe che la [resistenza alla censura]() ne risulterebbe incrementata.

**La teoria non riconosce che il controllo sulla selezione delle transazioni rimane in capo all'operatore della _pool_**, ed è quindi invalida. L'unico beneficio consiste nella riduzione della [varianza](), ma questo si registra solo quando il pagamento viene ricevuto. Poiché il pagamento è discrezionale, ad esso può essere teoricamente associato ogni tipo di condizione. Le condizioni potrebbero includere la censura e l'[identità](ch101-glossary.md#identità). I membri possono ricorrere all'abbandono della _pool_ in favore di un'altra, così come potrebbero ricorrenre al raggruppamento con condizione di accoppiamento (n.d.t. tra selezione delle transazioni e ricompensa). Per questa ragione le _pool_ disaccoppiate e quelle accoppiate sono egualmente soggette alla [cooptazione](ch101-glossary.md#cooptazione-co-option).

Vi è una teoria correlata secondo la quale la trasparenza di una _pool_ che impiega il disaccoppiamento è maggiore di quella di una _pool_ che usa l'accoppiamento, cosa che facilita la fuga dei suoi membri verso le _pool_ che non adottano la censura, limitando quindi la dominanza delle _pool_ che adottano censura. Anche accettando generosamente le assunzioni di maggiore trasparenza e il fatto che miner indipendenti agiscano contro il proprio stesso interesse finanziario, la questione della cooptazione rimane comunque irrisolta. Lo [stato](ch101-glossary.md#stato) può sempre riservare a sé stesso l'abilità di operare con i [vantaggi finanziari del raggruppamento](ch039-pooling-pressure-risk.md) e la teoria è quindi invalida.    

Questa fallacia è simile alla [Fallacia della Propagazione](ch075-relay-fallacy.md) che sostiene che tutti i vantaggi finanziari dipendono da miner altrimenti indipendenti che affidano ad una singola [persona](ch101-glossary.md#persona) il controllo di quello specifico vantaggio.

---

Titolo originale: [Decoupled Mining Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Decoupled-Mining-Fallacy)

[Indice](/README.md)

