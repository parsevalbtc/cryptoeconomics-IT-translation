# Difetto dello Sconto di Varianza



La [varianza](ch101-glossary.md#varianza) è la frequenza variabile con la quale viene ottenuta una [ricompensa](ch101-glossary.md#ricompensa-reward). La varianza è intrinseca alla natura probabilistica del mining e non può essere eliminata.

Per come è strutturato il [consenso](ch101-glossary.md#consenso), differenti [_hash power_](ch101-glossary.md#hash-power) tra i [miner](ch101-glossary.md#miner) implicano che le ricompense verranno guadagnate da alcuni di essi con maggiore frequenza di altri.  Con il 10% di [_hash rate_](ch101-glossary.md#hash-rate) ci si aspetterebbe di essere ricompensati 10 volte più frequentemente di coloro che hanno l'1%. Tuttavia, i risultati effettivi non sono predicibili e possono variare significativamente. Per la presente discussione è tuttavia sufficiente assumere in ambo i casi una relazione di proporzionalità. In questo esempio, un miner riceve una ricompensa ogni 100 minuti e l'altro ogni 1000 minuti. Assumendo la stessa ricompensa per ogni [blocco](ch101-glossary.md#blocco), la grandezza della ricompensa è anch'essa proporzionale all'_hash power_.

Va poi considerato che un miner di piccole dimensioni potrebbe dover attendere anni prima di ricevere una ricompensa. Vi è inoltre la possibilità che un [centro di mining](ch101-glossary.md#centro-di-mining-mine) sia mal configurato e che non pervenga mai ad un risultato positivo. Nonostante sia ricompensato in maniera proporzionale, egli è obbligato a migliorare il suo [flusso di cassa](https://it.wikipedia.org/wiki/Flusso_di_cassa_operativo) al fine di ricevere una frazione della ricompensa più frequentemente. Per queste ragioni i miner sono portati a scontare i ritorni in base alla varianza. I miner di dimensioni più piccole convertiranno i loro [centri di mining](ch101-glossary.md#centro-di-mining-mine) in un insieme di singoli [dispositivi di mining](ch101-glossary.md#dispositivo-di-mining-grind) e pagheranno un miner [aggregatore](ch101-glossary.md#aggregazione) per ottenere una varianza ridotta. Evitare questa aggregazione è il razionale che sta alla base di [P2Pool](https://en.bitcoin.it/wiki/P2Pool), ma poiché la riduzione di varianza ottenuta da questo sistema è meno efficiente, la pressione al [raggruppamento](ch101-glossary.md#raggruppamento-pooling) è dominante.

Questa [pressione al raggruppamento](ch039-pooling-pressure-risk.md) basata sulla varianza deriva dall'unico livello di [difficoltà](ch101-glossary.md#difficoltà) della rete previsto dalle [regole di consenso](ch101-glossary.md#regole-di-consenso). **Nonostante possiedano un basso _hash power_, i piccoli miner devono competere ad una difficoltà più elevata che amplifica intrinsecamente la varianza**. Il [premio di prossimità](ch036-proximity-premium-flaw.md) rappresenta un'altra pressione al raggruppamento causata dal [consenso](ch101-glossary.md#consenso).

La [difesa](ch004-axiom-of-resistance.md) che Bitcoin _intende_ innalzare è la difesa del [mercato](ch101-glossary.md#mercato) contro le forze anti-mercato (dello [stato]((ch101-glossary.md#stato)). Per fare ciò è necessario che l'[_hash power_](ch101-glossary.md#hash-power) vanga distribuito in maniera estesa tra le [persone]((ch101-glossary.md#persona) in modo che esso sia difficile da [cooptare](ch101-glossary.md#cooptazione-co-option). Tuttavia, le pressioni al raggruppamento intrinseche al [consenso](ch101-glossary.md#consenso) lavorano contro questo obiettivo. Per questo motivo tale caratteristica è definita un difetto, sebbene non sia stato scoperto alcun modo per eliminarlo.

---

Titolo originale: [Variance Discount Flaw](https://github.com/libbitcoin/libbitcoin-system/wiki/Variance-Discount-Flaw)

[Indice](/README.md)

