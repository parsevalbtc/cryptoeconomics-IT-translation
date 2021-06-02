# Fallacia delle _Fee_ a Parte



Esiste una teoria secondo la quale le [_fee_](ch101-glossary.md#commissione-di-transazione-fee) _off-_[_chain_](ch101-glossary.md#catena) rappresentino un incentivo individuale che va  contro la sicurezza del sistema (rappresenterebbero un [incentivo economico incompatibile](https://en.wikipedia.org/wiki/Incentive_compatibility)). La teoria afferma che un [commerciante](ch101-glossary.md#commerciante) che paga un [miner](ch101-glossary.md#miner) "a parte" al fine di confermare le sue [transazioni](ch101-glossary.md#transazione) impedisce alle transazioni di altri commercianti di essere confermate, oppure che questa azione alza il costo di queste conferme dando vantaggio a coloro che accettano tali _fee_.

Un effetto di questi accordi è che un livello _storico_ medio delle _fee_ non può essere determinato attraverso l'analisi della catena (_chain analysis_). Il livello apparente sarebbe più basso del livello del [mercato](ch101-glossary.md#mercato). Questo può naturalmente portare coloro che effettuano le [spese](ch101-glossary.md#spend) a sottostimare un livello di _fee_ sufficiente. Tuttavia non vi è alcuna proprietà di Bitcoin che richiede che le _fee_ future eguaglino un qualche livello medio delle _fee_ del passato. La stima necessariamente si compensa, come per esempio ignorando le transazioni "gratuite" in [blocchi](ch101-glossary.md#blocco) pieni o usando la [deviazione standard](https://it.wikipedia.org/wiki/Scarto_quadratico_medio) per identificare i valori estremi. Ma la stima della _fee_ è solo una stima. I livelli attuali delle _fee_ rispondono alla competizione.

Un altro effetto di questo fenomeno è che livelli relativamente eterogenei delle _fee_ possono evidenziare che certe transazioni sono associate con questi accordi. Questo può contribuire a [tracciare](ch101-glossary.md#tracciamento-taint) la transazione del commerciante e/o la transazione [coinbase](ch101-glossary.md#coinbase) del miner. Ma poiché un tale tipo di accordo è una scelta fatta dal creatore di queste transazioni, non vi è alcuna perdita di privacy.

Non vi è alcun effetto sui livelli del mercato delle _fee_ o nella possibilità per altri di ottenere delle conferme. Se l'accordo si discosta dai livelli di mercato allora o il commerciante o il miner stanno accettando una perdita non necessaria. Questo comportamento non è differente da quello di un miner che conferma transazioni con _fee_ _on-chain_ al di sotto del livello di mercato o da quello di un commerciante che sovrastima le fee _on-chain_, rispettivamente. In ogni caso, non ci sarebbe alcun pericolo per la sicurezza del sistema anche se tutte le _fee_ venissero pagate _off-chain_.

Bitcoin fornisce un meccanismo per le _fee on-chain_ che fa in modo che una transazione possa ricompensare _ogni_ potenziale miner senza l'uso dell'[identità](ch101-glossary.md#identità). E' una comodità che preserva la privacy. **Se i miner e i commercianti preferiscono indebolire la loro stessa privacy attraverso operazioni aggiuntive, non vi è motivo di considerare ciò non desiderabile**. La teoria è quindi invalida.

Inoltre, a meno che l'[_hash power_](ch101-glossary.md#hash-power) di un miner sia il 100%, il commerciante deve accettare un ritardo nella conferma che è inversamente proporzionale all'_hash power_ di quel miner. La _fee_ a parte è offerta al tasso di mercato poiché altrimenti il miner incorrerebbe in un costo opportunità.

Vi è una teoria collegata secondo la quale accordi sulle _fee_ a parte costituiscono una pressione al raggruppamento. Se le _fee_ pagate sono coerenti con il mercato non può esserci effetto di raggruppamento. Le _fee_ al di sopra del mercato sono un sussidio di [stato](ch101-glossary.md#stato), in quanto dobbiamo trattare il sussidio come un fenomeno non economicamente razionale. Le _fee_ al di sotto del mercato sono una tassa, in quanto dobbiamo trattarle come una perdita non volontaria. Queste sono [distorsioni](ch101-glossary.md#distorsione) come lo è qualsiasi tipo di sussidio/tassa di stato e [non sono quindi unicamente presenti](ch039-pooling-pressure-risk.md) nelle _fee_ a parte. L'esistenza delle _fee_ a parte non rappresenta una nuova pressione al raggruppamento in aggiunta a quelle già esistenti nelle _fee_ _on-chain_ e la teoria è quindi invalida. 

---

Titolo originale: [Side Fee Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Side-Fee-Fallacy)

[Indice](/README.md)

