# Glossario



### Fondamenti

----

##### Persona

Decisore.



##### Macchina

Esecutore di istruzioni.



###  L'accordo

------

##### Bitcoin

L'insieme di principi che proteggono una [Moneta]() dallo [Stato]().

> I termini ed i principi sono stati definiti da Satoshi in "Bitcoin: A Peer-to-Peer Electronic Cash System".



##### Consenso

Un accordo tra [Persone](). 

> Indica anche l'insieme di persone che partecipano in un accordo.



##### Moneta

Un [Consenso]() che riguarda un mezzo di [Scambio]() mutuamente accettato.



##### Regole di Consenso

L'insieme di vincoli che definisce una [Moneta]().



##### Regola

Un sottoinsieme delle [Regole di Consenso]().



##### Validità

Conformità alle [Regole di Consenso]().



##### Validazione

Il Processo volto a determinare la [Validità]().



  ##### Applicazione delle Regole (Enforcement)

L'atto di rigettare dati [Invalidi]().



### Oggetti

-------



##### Unità

Minima frazione di proprietà che può essere trasferita, rappresentata da una [Moneta]().

> Il Satoshi è l'unità di Bitcoin.



##### Trasferimento

Cambio di titolarità che coinvolge un certo numero di [Unità]().



##### Transazione

Registrazione [Validata]() di un [Trasferimento]().



##### Blocco

Insieme [Valido]() di [Transazioni]() dotate di [_Timestamp_]() e [Prova]().



##### Catena

[Ramo]() avente la maggior [Prova]() cumulata.



### Transazioni

-----



##### Script

Insieme di [Operazioni]() che autorizzano un [Trasferimento]().



##### Operazione

Dichiarazione  [atomica/univoca]  di intenti.



##### Contratto

[Script]() che esprime delle condizioni di [Trasferimento]().

> _Public Key Script_ è una formulazione anacronistica per questo termine.



##### (Verifica Positiva) (Endorsment)

Uno [Script]() che soddisfa un [Contratto]().

>Signature Script (ScriptSig) è una formulazione anacronistica per questo termine.



##### Point

Riferimento ad un [Output]() o ad un [Input]().



##### Output

Un [Trasferimento]() esplicito collegato ad un [Contratto]().



##### Input

Un [_Output_]() [_Point_]() collegato ad un [_Endorsment_]().

 

##### Output precedente 

L'[Output]() al quale si riferisce un [Input]().



##### Locktime

Una espressione relativa alla più recente [Validità]() di una [Transazione]().



##### Dust

Un numero insufficiente di [Unità]() necessarie per effettuare un [Trasferimento]() attraverso un [Output]().

> Le regole di consenso di Bitcoin proibiscono il trasferimento di meno di una unità



### Blocchi

------

##### Timestamp

Una dichiarazione relativa al tempo di produzione di un [Blocco]().



##### Tempo Mediano Trascorso 

Una media dei [Timestamp]() dei precedenti [Blocchi]().



##### Prova

Una dimostrazione probabilistica della quantità di [Lavoro]() svolta.



##### Branch - Ramo

Una sequenza [valida]() di [blocchi]().



##### Weak (Branch) - Ramo debole

Un [Branch]() avente meno [Prova]() cumulata rispetto ad un altro.

> Branch orfano è un nome fuorviante di questo termine.



##### Strong (Branch) - Ramo forte

Un [Branch]() avente più [Prova]() cumulata rispetto ad un altro.



### Sequenza

-----

##### Conferma

Inclusione di una [Transazione]() in un [Blocco]().



##### Non Confermata

Una [Transazione]() che non è inclusa in alcun [Blocco]().



##### Transaction Pool - Pool delle transazioni 

L'insieme delle [Transazioni]() [Non Confermate]().

> Memory Pool è un nome fuorviante per questo termine.



##### Block Pool

L'insieme dei [blocchi]() [deboli]().

> Pool dei Blocchi Orfani è un nome fuorviante di questo termine.



##### Genesi

Il primo [Blocco]() di tutti i [Rami]() di una [Moneta]().



##### Profondità - Depth

Uno più il numero di [Blocchi]() dopo una [Conferma]().



##### Altezza

Il numero di blocchi precedenti [Contenuti]() in un [Ramo]().



##### Segmento 

Un sottoinsieme contiguo (di blocchi) in un [Ramo]().



##### Organizzazione 

Un [Annuncio]() relativo all'aggiunta di un [Blocco]() alla [Catena]().



##### Periodo

Tempo medio trascorso tra due [Organizzazioni]().



##### Stratificazione (Layering)

[Scambio]() effettuato utilizzando una sequenza di [Transazioni]() [Non Confermate]() che possono essere [Finalizzate]() da ambo le [Controparti]().



##### Settlement - Finalizzazione

[Conferma]() di [Transazioni]() [Layerizzate]().



### Moneta

------

##### Spesa

La prima pubblicazione di una [Transazione]().



##### Doppia Spesa

_[Endorsment]()_ dello stesso [Output]() in due [Spese]() distinte.



##### Sussidio (Subsidy)

Emissione di nuove [Unità]() ad un [Miner]().



##### Inflazione 

L'aumento di [Offerta]() dovuta al [Sussidio]().

> Il termine si riferisce all'inflazione monetaria che non va confusa con l'inflazione dei prezzi.



##### Commissione di Transazione (Fee)

Un [Trasferimento]() implicito ad un [Miner]().



##### Ricompensa (Reward)

 La somma del [Sussidio]() e delle [Commissioni]() per un [Blocco]().



##### Coinbase 

Una [Transazione]() che trasferisce la [Ricompensa]() (di un Blocco).



##### Maturità

La [Profondità]() alla quale un [Output]() della [Coinbase]() diventa [Trasferibile]().



##### Dimezzamento (Halving)

Riduzione (pari alla metà) della quantità di [Sussidio]().



##### Difficoltà

Il livello di [Prova]() richiesto per la [Validità]().



##### Aggiustamento 

Cambiamento nella [Difficoltà]().



##### Cap

Il limite posto [all'Offerta]() nel tempo.



##### Prezzo

Media variabile di valori di [Scambio]().



##### Capitalizzazione

Prodotto del [Prezzo]() per [l'Offerta]()



### Economia

----

##### Scambio

Passaggio volontario di proprietà tra due [Persone]().



##### Utilità

Il grado di Utilità di una certa proprietà per una [Persona]().



##### Valore

La preferenza accordata da una [Persona]() su una proprietà rispetto ad un altra.



##### Offerta 

L'insieme ti tutte le [Unità]() emesse.



##### Scambio monetario

Lo [scambio]() di [Unità]() monetarie per altra proprietà.



##### Inflazione del prezzo

Aumento nel prezzo medio di [scambio monetario]() nel tempo.



##### Accumulare

[Possedere]() per un uso futuro.

> Non si tratta né di speculazione né di investimento.



##### Speculare

[Possedere]() nell'aspettativa di un aumento di [Prezzo]().

> In maniera equivalente anche dare in prestito nell'aspettativa di una diminuzione del prezzo.



##### Dare in prestito - Investire

[Scambiare]() tempo privandosi di [Unità]() per acquisire (nel futuro) una proprietà di maggiore [Utilità]().



##### Prendere a prestito

[Scambiare]() tempo per [Unità]() che garantiscono al [Prestatore]() maggiore [Utilità]() (nel futuro).



##### Interesse

Il tasso relativo all'aumento di Utilità nel [Dare in prestito]().



##### Profitto

Il ritorno (economico) derivante dalla [Speculazione]()

>Ciò esclude l'interesse



##### Perdita

Fallimento nel percepire [l'Interesse]() in un [Investimento]().

> Si tratta di profitto negativo.



##### Volatilità

Deviazioni del [Prezzo]() che avvengono nel tempo.



##### Mercato

Lo [Scambio]() di certe proprietà.



### Network

-----

##### Comunicazione

Trasmissione di dati tra due Macchine.



##### Protocollo

Un insieme di convenzioni adottate nella [Comunicazione]().



##### Peer-to-Peer

Un [Protocollo]() simmetrico.



##### Client-Server

Un [Protocollo]() asimmetrico.



##### Latenza

Il ritardo intrinseco nella [Comunicazione]().



##### Partizione

Una impossibilità di certi [Nodi]() di [Comunicare]().



##### Diniego di Servizio (Denial of Service) 

Utilizzare la [Comunicazione]() per sfruttare falle nel [Protocollo]() o [nell'Implementazione]() che portano a degradare le prestazioni.

> DoS è un acronimo di questo termine.



### Componenti

--------

##### Centro di Mining (Mine)

Uno [Strumento]() che compie [Lavoro]().



##### Dispositivo di Mining (Grinder) 

Uno [Strumento]() che compie operazioni di [Hashing]().



##### Propagatore (Relay)

Uno [Strumento]() che propaga nuovi [Blocchi]().



##### Nodo

Uno [Strumento]() che esegue l'operazione di [Validazione]().



##### Wallet 

Uno [Strumento]() che crea [Transazioni](). 



##### Strumento (Tool)

Un insieme di istruzioni [Macchina]().



##### Implementazione 

Uno specifico insieme di [Strumenti]().



### Attori

-------

##### Miner

Una [Persona]() che opera un [Centro di Mining](). 



##### Operatore di Dispositivo di Mining (Grinder)

Una [Persona]() che opera un [Dispositivo di Mining]().



##### Relayer 

Una Persona che opera un Propagatore ([Relay]()).



##### Commerciante

Una [Persona]() che accetta [Unità]() in uno [Scambio]().

> Utente è un sinonimo comune di questo termine.



##### Proprietario

Una [Persona]() che ha il controllo di certe [Untità]().

> Detentore è un sinonimo comune di questo termine.



##### Sviluppatore (Developer)

Una [Persona]() che crea una [Implementazione]().



##### Ricorrente (Claimant)

Una [Persona]() che detiene un titolo di una proprietà sotto il controllo di un Custode.



##### Custode (Custodian)

Una [Persona]() che controlla la proprietà di un'altra.



### Mining

-------

##### Lavoro

Il processo di produzione di un [Blocco]().



##### Candidato

Un [Blocco]() potenziale con una [Prova]() non definita.



##### Hash

Una singola computazione svolta per [Provare]() la [Validità]() di un [Candidato](). 



##### Hash Rate

La quantità di [Hash]() calcolati nell'unità di tempo.



##### Hash Power Apparente

Un frazione di [Blocchi]() in un [Segmento]() di [Catena]().

> Le stime pubbliche dell'hash power di un miner sono basate su questa definizione.



##### Maggioranza dell'Hash Power

Un sottoinsieme di [Miner]() dotato di sufficiente Hash Power tale da compiere un [Attacco]() sostenuto nel tempo.

> 51% è una comune approssimazione di sufficiente hash power. 



##### Ottimizzazione

Uno [Strumento]() che riduce il costo del [Mining]().



##### Annuncio

La prima comunicazione di un [Blocco]() ad un altra [Persona]().



##### Trattenimento (Withholding)

Il ritardo intenzionale di un [Annucio]().



##### Onesto

Un [Miner]() che costruisce sui [Blocchi]() di altri.



##### Selfish

Un [Miner]() che non si dimostra sempre [Onesto]().



##### Varianza

La frequenza variabile con cui si ottiene la [Ricompensa]().



##### Disaccoppiamento (Decouple)

Un [Centro di Mining]() che condivide la [Ricompensa]() con un altro al fine di ridurre la [Varianza]().



### Deviazioni

------

##### Fork

Una divergenza nelle [Regole di Consenso]().



##### Hard Fork

Un [Fork]() che implica una [Separazione]().



##### Soft Fork

Un [Fork]() che implica una [Separazione]() a meno che il cambiamento nelle regole non sia [Applicato]() dalla [Maggioranza dell'Hash Power]().

> Si riduce l'insieme dei blocchi potenzialmente validi.



##### Separazione (Split)

Una biforcazione di una [Moneta]().



##### Riorganizzazione

Un Annuncio che promuove un [Ramo Debole]() sulla [Catena]().

> Reorg è una abbreviazione di questo termine.



##### Stallo

L'assenza di incremento di [Altezza]() nel tempo.



##### Attivazione

Iniziare ad [Applicare]() una nuova [Regola]().



##### Segnalazione (Signal)

Una indicazione di un [Miner]() veicolata dai dati di un [Blocco]() relativa all'intenzione di [Applicare]() una nuova [Regola](). 



### Privacy

------

##### Identità

I modi di associare una [Comunicazione]() ad una [Persona]().



##### Tracciamento (Taint)

Determinazione della [Proprietà]().



### Sicurezza

-----

##### Potere 

Il livello relativo di controllo di una [Persona]() su una [Catena]() o una [Moneta]().



##### Economia

L'insieme di tutti i [Commercianti]().



##### Potere Economico

Una frazione di tutte le proprietà offerte in [Scambio]().



##### Hash Power

Una frazione dell'[Hash Rate]() di tutti i [Centri di Mining]().



##### Attacco 

Utilizzo di [Hash Power]() al fine di realizzare una [Doppia Spesa]().



##### Cooptazione (Co-option)

Ricorso all'aggressione al fine di controllare dell'[HashPower]().



##### Coercizione

Ricorso all'aggressione al fine di indurre ad una [Attivazione]().



##### Distorsione

Aggressione di [Mercato]() che altera il costo del [Mining]().



##### Variazione

Differenze nel costo della risorsa per il [Mining]().



##### Censura

[Conferma]() soggettiva.



##### Stato

Insieme di [Persone]() che utilizzano l'aggressione al posto dello [Scambio]().

> Opera tipicamente in un regime di impunità all'interno di limiti geografici.



##### Politico

Che concerne le azioni degli [Stati]().



### Debolezza

------

##### Aggregazione

La Tendenza alla ridotta partecipazione nel Mining o nella Validazione.

> Implica il raggruppamento o la centralizzazione.



##### Raggruppamento (Pooling)

La tendenza verso l'esistenza di pochi [Miner](), che include il consolidamento dei [Propagatori]().

> Collusione è un comune sinonimo per questo termine.



##### Centralizzazione

La tendenza verso l'esistenza di pochi [Commercianti]().

> I Commercianti controllano direttamente la validazione.



##### Delegazione

La tendenza verso l'esistenza di pochi [Proprietari]().

> I Proprietari controllano direttamente la spesa.



##### Partizionamento

La tendenza verso [Partizioni]() persistenti.

> L'identità implica l'esclusione.



##### Correlazione

L'abilità di Tracciare usando metodi statistici di _[Chain]()_ analysis.































