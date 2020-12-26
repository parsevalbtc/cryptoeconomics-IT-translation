# Difetto dello Sconto di Varianza



La [varianza](ch101-glossary.md#varianza) è la frequenza variabile con la quale viene ottenuta una [ricompensa](ch101-glossary.md#ricompensa-reward). La varianza è intrinseca alla natura probabilistica del mining e non può essere eliminata.

Per come è strutturato il [consenso](ch101-glossary.md#consenso), differenti [_hash power_](ch101-glossary.md#hash-power) tra i [miner]() implicano che le ricompense verranno guadagnate da alcuni di essi con maggiore frequenza di altri.  Con il 10% di _hash power_ ci si aspetterebbe di essere ricompensati 10 volte più frequentemente di coloro che hanno l'1%, sebbene il fattore moltiplicativo sia in realtà più elevato a causa del [premio di prossimità](ch036-proximity-premium-flaw.md). Tuttavia, i risultati effettivi non sono predicibili e possono variare significativamente. Per la presente discussione è tuttavia sufficiente assumere in ambo i casi una relazione di proporzionalità. In questo esempio un miner riceve una ricompensa ogni 100 minuti e l'altro ogni 1000 minuti. Assumendo la stessa ricompensa per ogni [blocco](ch101-glossary.md#blocco), la grandezza della ricompensa è anch'essa proporzionale all'_hash power_.

Va considerato inoltre che un miner di piccole dimensione potrebbe dover attendere anni prima di ricevere una ricompensa. Nonostante un miner di dimensioni più piccole sia remunerato in maniera proporzionale egli deve affrontare questo difetto rispetto ad un miner di dimensioni maggiori. Egli può tuttavia migliorare il suo [flusso di cassa](https://it.wikipedia.org/wiki/Flusso_di_cassa_operativo) ricevendo una frazione della ricompensa più frequentemente. Vi è anche la possibilità che un centro di mining non sia ben configurato e che non pervenga mai ad un risultato positivo. Per queste ragioni i miner sono portati a scontare la varianza elevata. I miner di dimensioni più piccole convertiranno i loro [centri di mining](ch101-glossary.md#centro-di-mining-mine) in un insieme di singoli [dispositivi di mining](ch101-glossary.md#dispositivo-di-mining-grind) e pagheranno un miner aggregatore per ottenere una varianza ridotta. Questo è il fondamento logico che sta alla base di [P2Pool](https://en.bitcoin.it/wiki/P2Pool) ma poiché la riduzione di varianza ottenuta da questo sistema è meno efficiente, la pressione al [raggruppamento](ch101-glossary.md#raggruppamento-pooling) rimane.

La [pressione al raggruppamento](ch039-pooling-pressure-risk.md) basata sulla varianza è dovuta dell'unico livello di [difficoltà](ch101-glossary.md#difficoltà) della rete previsto dalle [regole di consenso](ch101-glossary.md#regole-di-consenso). **Nonostante possiedano un basso _hash power_ , i piccoli miner devono competere ad una difficoltà più elevata che amplifica intrinsecamente la varianza**. Il [premio di prossimità](ch036-proximity-premium-flaw.md) rappresenta un'altra pressione al raggruppamento causata dal consenso.

La [difesa](ch004-axiom-of-resistance.md) che Bitcoin _intende_ innalzare è la difesa del mercato contro le forze anti-mercato. Per fare ciò è necessario distribuire l'[_hash power_](ch101-glossary.md#hash-power) in maniera estesa tra le persone in modo che esso sia difficile da [cooptare](ch101-glossary.md#cooptazione-co-option).  Tuttavia la pressione al raggruppamento intrinseca al [consenso]() lavora contro questo obiettivo. Questo è il motivo per il quale questa caratteristica è definita un difetto.

---------
Titolo originale: [Variance Discount Flaw](https://github.com/libbitcoin/libbitcoin-system/wiki/Variance-Discount-Flaw)

[Indice](/README.md)

