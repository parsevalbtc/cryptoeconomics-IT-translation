# Fallacia del Blocco Vuoto



Esiste una teoria secondo la quale il [minare]() [blocchi]() vuoti rappresenti un [attacco](). La teoria non richiede che i blocchi siano minati su un [ramo]() [debole]() nel tentativo di permettere la [doppia spesa](),  né essa specificato quale [persona]() sia attaccata.

Si prendano in considerazione quanto segue:

* Il termine "attacco" implica il furto. Il [_whitepaper_ di Bitcoin](), ad esempio, utilizza il termine solamente per descrivere i tentativi di doppia spesa.
* Una [ricompensa]() di un blocco è costituita da [_fee_]() per le [transazioni]() e da un [sussidio](). Il [miner]() che rinuncia alle fee di transazione non includendole (in un blocco) non è remunerato da esse.
* L'[_hash power_]() del miner contribuisce in maniera proporzionale alla sicurezza del network. Il sussidio rappresenta la compensazione per la sicurezza durante la fase [inflazionaria](). Lo scopo dell'inflazione è quello di distribuire razionalmente le [unità]() [di Bitcoin]. La distribuzione razionale è [scambiata]() specificamente in cambio di _hash power_, non al fine di includere transazioni.
* La [conferma]() di transazioni non è garantita. Le _fee_ sono l'incentivo per la conferma. La mancanza di conferme implica in maniera obiettiva l'insufficienza delle fee.
* I blocchi vuoti sono completamente compatibili alle [regole del consenso]() e non possono essere ragionevolmente impedite da una nuova [regola]().

Per queste ragioni la teoria è invalida. Tuttavia risulta utile investigare la causa della fallacia. A causa della [proprietà della somma zero](), può essere assunto che minare un blocco vuoto "slealmente" possa togliere la possibilità alle transazioni di essere confermate.

Altri miner hanno la capacità di confermare transazioni in proporzione al loro _hash power_. Se il 10% dell'_hash power_ mina blocchi vuoti, le conferme richiederanno in media il 10% in più del tempo. Tuttavia se un miner rimuove 10% dell'_hash power_ totale, le conferme richiederanno sempre il 10% in più del tempo in media, fino al successivo [aggiustamento]() della difficoltà. Tuttavia rimuovere il proprio _hash power_ non è generalmente considerato un attacco.

Un miner impegna del capitale per minare, producendo, in ritorno, dell'_hash power_. Tenendo da parte gli [effetti del _pooling_](), il miner viene sovvenzionato in proporzione all'_hash power_ prodotto. Senza questo _hash power_ altri miner produrrebbero lo stesso numero medio di blocchi ad una [difficoltà]() proporzionalmente minore. In altre parole, un attacco _reale_ sarebbe proporzionalmente meno costoso. Così, nonostante il miner non venga remunerato per includere transazioni [nel blocco], egli sta rendendo sicure le transazioni precedentemente confermate.

Poiché il [costo marginale]() di includere una transazione è al di sotto dei livelli medi delle _fee_, il miner che mina un blocco vuoto sta subendo un [costo-opportunità](). Questo costo ammonta al livello per il quale il miner sta sussidiando la sicurezza della [catena](). Nonostante questo comportamento sembri economicamente irrazionale nel contesto limitato della moneta, esso può considerarsi razionale a causa del costo-opportunità bilanciato dal tempo di attesa di un blocco [candidato]() non vuoto che segue un [annuncio]().

Nonostante un certo miner possa considerare vantaggioso minare blocchi vuoti, è nel [potere]() di qualsiasi altra persona fare altrimenti. E' la facoltà di [esercitare questa opportunità]() che rende sicura la moneta, anche contro attacchi _reali_. **Esporre alla critica queste azioni dettate dal proprio interesse è inefficace e controproducente. 





