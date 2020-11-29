# Difetto dello Sconto di Varianza



La [varianza]() è la frequenza variabile con la quale viene ottenuta una [ricompensa](). La Varianza è intrinseca alla natura probabilistica del mining e non può essere eliminata.

Per come è strutturato il [consenso](), differenti  [_hash power_]() tra i [miner]() implicano che le ricompense verranno guadagnate da alcuni con maggiore frequenza di altri.  Con il 10% di _hash power_ ci si aspetterebbe di essere ricompensati 10 volte più frequentemente di coloro che hanno l'1%, sebbene il fattore moltiplicativo sia in realtà più elevato a causa del [premio di prossimità](). I risultati effettuali, tuttavia, non sono predicibili e possono variare significativamente. Ma per la presente discussione è sufficiente in ambo i casi assumere una relazione di proporzionalità. In questo esempio un miner riceve una ricompensa ogni 100 minuti e l'altro ogni 100 minuti. Assumendo la stessa ricompensa per ogni [blocco](), la grandezza della ricompensa è proporzionale all'_hash power_.

Si consideri poi che un miner di piccole dimensione potrebbe dover attendere anni prima di ricevere una ricompensa. Nonostante sia remunerato in maniera proporzionale un miner di dimensioni più piccole percepisce una inadeguatezza rispetto ad un miner di dimensioni maggiori. Egli può tuttavia migliorare il suo [flusso di cassa]() ricevendo una frazione della ricompensa più frequentemente. Vi è anche la possibilità che una [_ming farm_] non sia ben configurata e che non pervenga mai ad un risultato positivo. Per queste ragioni i miner sono portati a scontare la varianza elevata. I miner di dimensioni più piccole convertiranno le loro [_mining farm_]() in un insieme di singoli [dispositivi di mining]() e pagheranno un miner aggregatore per la ridotta varianza. Questo è il razionale che sta alla base di [P2Pool](), ma poiché la varianza ridotta dalla distribuzione [dell'_hash power_] è meno efficiente, la pressione all'aggregazione (pooling) rimane.

La pressione all'aggregazione basata sulla varianza è una conseguenza dell'unico livello di [difficoltà]() dovuto alle [regole di consenso](). **I piccoli miner devono competere ad una difficoltà più elevata nonostante il basso _hash power_che amplifica la varianza intrinseca**. Il [premio di prossimità]() è un'altra pressione all'aggregazione causata dal consenso.

La [difesa]() che Bitcoin _intende_ elevare è la difesa del mercato contro le forze anti-mercato. Per fare ciò deve distribuire [hash power_ ]() tra le persone in maniera diffusa in modo che sia difficile da [cooptare]().  Tuttavia la pressione di aggregazione intrinseca al [consenso]() lavora contro questo obiettivo. Questo è il motivo per il quale questa caratteristica è definita un difetto.



