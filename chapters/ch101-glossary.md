# Glossario



## Fondamenti


#### Persona

Decisore.

#### Macchina

Esecutore di istruzioni.



##  L'accordo



#### Bitcoin

L'insieme di principi che proteggono una [Moneta](#moneta) dallo [Stato](#stato).

> I termini ed i principi sono stati definiti da Satoshi in "Bitcoin: A Peer-to-Peer Electronic Cash System".



#### Consenso

Un accordo tra [Persone](#persona). 

> Indica anche l'insieme di persone che partecipano in un accordo.



#### Moneta

Un [Consenso](#consenso) che riguarda un mezzo di [Scambio](#scambio) mutuamente accettato.



#### Regole di Consenso

L'insieme dei vincoli che definisce una [Moneta](#moneta).



#### Regola

Un sottoinsieme delle [Regole di Consenso](#regole-di-consenso).



#### Validità

Conformità alle [Regole di Consenso](#regole-di-consenso).



#### Validazione

Il Processo volto a determinare la [Validità](#validità).



  #### Applicazione delle Regole (Enforcement)

L'atto di rigettare dati [Invalidi](#validità).



## Oggetti



#### Unità

Minima frazione di proprietà che può essere trasferita e rappresentata da una [Moneta](#moneta).

> Il Satoshi è l'unità di Bitcoin.



#### Trasferimento

Cambio di titolarità che coinvolge un certo numero di [Unità](#unità).



#### Transazione

Registrazione [Validata](#validità) di un [Trasferimento](#trasferimento).



#### Blocco

Insieme [Valido](#validità) di [Transazioni](#transazione) dotate di [_Timestamp_](#marcatura-temporale-timestamp) e [Prova](#prova).



#### Catena

[Ramo](#ramo-branch) avente la maggior [Prova](#prova) cumulata.



## Transazioni


#### Script

Insieme di [Operazioni](#operazione) che autorizzano un [Trasferimento](#trasferimento).



#### Operazione

Dichiarazione atomica (univoca) di intenti.



#### Contratto

[Script](#script) che esprime delle condizioni di [Trasferimento](#trasferimento).

> _Public Key Script_ è una formulazione anacronistica per questo termine.



#### Endorsement

Uno [Script](#script) che soddisfa un [Contratto](contratto).

>Signature Script (ScriptSig) è una formulazione anacronistica per questo termine.



#### Point

Riferimento ad un [Output](#output) o ad un [Input](#input).



#### Output

Un [Trasferimento](#trasferimento) esplicito collegato ad un [Contratto]().



#### Input

Un [_Output_](#output) [_Point_](#point) collegato ad un [_Endorsment_](#endorsement).

 

#### Output precedente 

L'[Output](#output) al quale si riferisce un [Input](#input).



#### Locktime

Un'espressione relativa alla più recente [Validità](#validità) di una [Transazione](#transazione).



#### Dust

Un numero insufficiente di [Unità](#unità) necessarie per effettuare un [Trasferimento](#trasferimento) attraverso un [Output](#output).

> Le regole di consenso di BTC proibiscono il trasferimento di meno di una unità



## Blocchi


#### Marcatura Temporale (Timestamp)

Una dichiarazione relativa al tempo di produzione di un [Blocco](#blocco).



#### Tempo Mediano Trascorso 

Una media dei [_Timestamp_](#marcatura-temporale-timestamp) dei precedenti [Blocchi]().



#### Prova

Una dimostrazione probabilistica della quantità di [Lavoro](#lavoro) svolta.



#### Ramo (Branch)

Una sequenza [Valida](#validità) di [Blocchi](#blocchi).



#### Ramo debole (eak Branch)

Un [Ramo](#ramo-branch) avente meno [Prova](#prova) cumulata rispetto ad un altro.

> Ramo orfano è un nome fuorviante di questo termine.



#### Ramo forte (Strong Branch)

Un [Ramo](#ramo-branch) avente maggiore [Prova](#prova) cumulata rispetto ad un altro.



## Sequenza



#### Conferma

Inclusione di una [Transazione](#transazione) in un [Blocco](#blocco).



#### Non Confermata

Una [Transazione](#transazione) che non è inclusa in alcun [Blocco](#blocco).



#### Transaction Pool 

L'insieme delle [Transazioni](#transazione) [Non Confermate](#non-confermata).

> Memory Pool (Mempool) è un nome fuorviante per questo termine.



#### Block Pool

L'insieme dei [Blocchi](#blocco) [Deboli](#ramo-debole-weak-branch).

> Pool dei Blocchi Orfani è un nome fuorviante di questo termine.



#### Blocco Genesi

Il primo [Blocco](#blocco) di tutti i [Rami](#ramo-branch) di una [Moneta](#moneta).



#### Profondità (Depth)

Il numero di [Blocchi](#blocco) più uno dopo una [Conferma](#conferma).



#### Altezza (Height)

Il numero di [blocchi](#blocco) precedenti contenuti in un [Ramo](#ramo).



#### Segmento 

Un sottoinsieme contiguo (di blocchi) in un [Ramo](#ramo-branch).



#### Organizzazione 

Un [Annuncio](#annuncio) relativo all'aggiunta di un [Blocco](#blocco) alla [Catena](#catena).



#### Periodo

Tempo medio trascorso tra due [Organizzazioni](#organizzazione).



#### Layering

[Scambio](#scambio) effettuato utilizzando una sequenza di [Transazioni](#transazione) [Non Confermate](#non-confermata) che possono essere [Finalizzate](#finalizzazione-settlement) da ambo le Controparti.



#### Finalizzazione (Settlement)

[Conferma](#conferma) di [Transazioni](#transazione) [Layerizzate](#layering).



## Denaro



#### Spesa

La prima pubblicazione di una [Transazione](#transazione).



#### Doppia Spesa

_[Endorsment](#endorsment)_ dello stesso [Output](#output) in due [Spese](#spesa) distinte.



#### Sussidio (Subsidy)

Emissione di nuove [Unità](#unità) ad un [Miner](#miner).



#### Inflazione 

L'aumento di [Offerta](#offerta) dovuta al [Sussidio](#sussidio-subsidy).

> Il termine si riferisce all'inflazione monetaria che non va confusa con l'inflazione dei prezzi.



#### Commissione di Transazione (Fee)

Un [Trasferimento](#trasferimento) implicito ad un [Miner](#miner).



#### Ricompensa (Reward)

 La somma del [Sussidio](#sussidio-subsidy) e delle [Commissioni](#commissione-di-transazione-fee) per un [Blocco](#blocco).



#### Coinbase 

Una [Transazione](#transazione) che trasferisce la [Ricompensa](#ricompensa-reward) (di un Blocco).



#### Maturità

La [Profondità](#profondità-depth) alla quale un [Output](#output) della [Coinbase](#coinbase) diventa [Trasferibile](#trasferimento).



#### Dimezzamento (Halving)

Riduzione (pari alla metà) della quantità di [Sussidio](#sussidio-subsidy).



#### Difficoltà

Il livello di [Prova](#prova) richiesto per la [Validità](#validità).



#### Aggiustamento 

Cambiamento nella [Difficoltà](#difficoltà).



#### Limite (Cap)

Il limite posto all'[Offerta](#offerta) nel tempo.



#### Prezzo

Media variabile di valori di [Scambio](#scambio-di-unità).



#### Capitalizzazione

Prodotto del [Prezzo](#prezzo) per l'[Offerta](#offerta)



## Economia



#### Scambio

Passaggio volontario di proprietà tra due [Persone](#persona).



#### Utilità

Il grado di beneficio che ha una certa proprietà per una [Persona](#persona).



#### Valore

La preferenza accordata da una [Persona](#persona) su una proprietà rispetto ad un altra.



#### Offerta 

L'insieme di tutte le [Unità](#unità) emesse.



#### Scambio di Unità

Lo [Scambio](#scambio) di [Unità](#unità) per altra proprietà.



#### Inflazione di prezzo

Aumento nel prezzo medio di [Scambio](#scambio-di-unità) nel tempo.



#### Accumulare

[Possedere](#proprietario) per un uso futuro.

> Non si tratta né di speculazione né di investimento.



#### Speculare

[Possedere](#proprietario) nell'aspettativa di un aumento di [Prezzo](#prezzo).

> In maniera equivalente anche dare in prestito nell'aspettativa di una diminuzione del prezzo.



#### Dare in Prestito - Investire

[Scambiare](#scambio) tempo privandosi di [Unità](unità) per acquisire (nel futuro) una proprietà di maggiore [Utilità](#utilità).



#### Prendere a Prestito

[Scambiare](#scambio) tempo per [Unità](#unità) che garantiscono al [Prestatore](#dare-in-prestito---investire) maggiore [Utilità](#utilità) (nel futuro).



#### Interesse

Il tasso relativo all'aumento di [Utilità](#utilità) nel [Dare in prestito](#dare-in-prestito---investire).



#### Profitto

Il ritorno (economico) derivante dalla [Speculazione](#speculare)

>Ciò esclude l'interesse



#### Perdita

Fallimento nel percepire l'[Interesse](#interesse) in un [Investimento](#dare-in-prestito---investire).

> Si tratta di profitto negativo.



#### Volatilità

Variazioni del [Prezzo](#prezzo) che avvengono nel tempo.



#### Mercato

Lo [Scambio](#scambio) di certe proprietà.



## Network



#### Comunicazione

Trasmissione di dati tra due [Macchine](#macchina).



#### Protocollo

Un insieme di convenzioni adottate nella [Comunicazione](#comunicazione).



#### Peer-to-Peer

Un [Protocollo](#protocollo) simmetrico.



#### Client-Server

Un [Protocollo](#protocollo) asimmetrico.



#### Latenza

Il ritardo intrinseco nella [Comunicazione](#comunicazione).



#### Partizione

Una impossibilità di certi [Nodi](#nodo) di [Comunicare](#comunicazione).



#### Denial of Service

Utilizzare la [Comunicazione](#comunicazione) per sfruttare difetti nel [Protocollo](#protocollo) o nell'[Implementazione](#implementazione) che portano a degradare le prestazioni.

> DoS è un acronimo di questo termine.



## Componenti



#### Centro di Mining (Mine)

Uno [Strumento](#strumento-tool) che compie [Lavoro](#lavoro).



#### Dispositivo di Mining (Grind) 

Uno [Strumento](#strumento-tool) che compie operazioni di [Hashing](#hash).



#### Propagatore (Relay)

Uno [Strumento](strumento-tool) che propaga nuovi [Blocchi](#blocco).



#### Nodo

Uno [Strumento](strumento-tool) che esegue l'operazione di [Validazione](#validità).



#### Wallet 

Uno [Strumento](strumento-tool) che crea [Transazioni](#transazione). 



#### Strumento (Tool)

Un insieme di istruzioni [Macchina](#macchina).



#### Implementazione 

Uno specifico insieme di [Strumenti](strumento-tool).



## Attori



#### Miner

Una [Persona](#persona) che opera un [Centro di Mining](centro-di-mining-mine). 



#### Operatore di Dispositivo di Mining (Grinder)

Una [Persona](#persona) che opera un [Dispositivo di Mining](#dispositivo-di-mining-grinder).



#### Relayer 

Una Persona che opera un Propagatore ([Relay](#propagatore-relay)).



#### Commerciante

Una [Persona](#persona) che accetta [Unità](unità) in uno [Scambio](#scambio).

> Utente è un sinonimo comune di questo termine.



#### Proprietario

Una [Persona](#persona) che ha il controllo di certe [Untità](#unità).

> Detentore è un sinonimo comune di questo termine.



#### Sviluppatore (Developer)

Una [Persona](#persona) che crea una [Implementazione](#implementazione).



#### Ricorrente (Claimant)

Una [Persona](#persona) che detiene un titolo di una proprietà sotto il controllo di un [Custode](#custode-custodian).



#### Custode (Custodian)

Una [Persona](#persona) che controlla la proprietà di un'altra.



## Mining



#### Lavoro

Il processo di produzione di un [Blocco](#blocco).



#### Candidato

Un [Blocco](#blocco) potenziale con una [Prova](#prova) non definita.



#### Hash

Una singola computazione svolta per [Provare](#prova) la [Validità](#validità) di un blocco [Candidato](#candidato). 



#### Hash Rate

La quantità di [Hash](#hash) calcolati nell'unità di tempo.



#### Hash Power Apparente

Un frazione di [Blocchi](#blocco) in un [Segmento](#segmento) di [Catena](#catena).

> Le stime pubbliche dell'hash power di un miner sono basate su questa definizione.



#### Maggioranza dell'Hash Power

Un sottoinsieme di [Miner](#miner) dotato di sufficiente [Hash Power](#hash-power) tale da compiere un [Attacco](#attacco) sostenuto nel tempo.

> 51% è una comune approssimazione di sufficiente hash power. 



#### Ottimizzazione

Uno [Strumento](strumento-tool) che riduce il costo del [Mining](#centro-di-mining-mine).



#### Annuncio

La prima comunicazione di un [Blocco](#blocco) ad un'altra [Persona](#persona).



#### Trattenimento (Withholding)

Il ritardo intenzionale di un [Annucio](#annuncio).



#### Onesto

Un [Miner](#miner) che costruisce sui [Blocchi](#blocco) di altri.



#### Selfish Miner

Un [Miner](#miner) che non si dimostra sempre [Onesto](#onesto).



#### Varianza

La frequenza variabile con cui si ottiene la [Ricompensa](#ricompensa-reward).



#### Disaccoppiamento (Decouple)

Un [Centro di Mining](#centro-di-mining-mine) che condivide la [Ricompensa](#ricompensa-reward) con un altro al fine di ridurre la [Varianza](#varianza).



## Deviazioni



#### Fork

Una divergenza nelle [Regole di Consenso](#regole-di-consenso).



#### Hard Fork

Un [Fork](#fork) che implica una [Separazione](#separazione-split).



#### Soft Fork

Un [Fork](#fork) che implica una [Separazione](#separazione-split) a meno che il cambiamento nelle regole non sia [Applicato](#applicazione-delle-regole-enforcement) dalla [Maggioranza dell'Hash Power](#maggioranza-dellhash-power).

> Si riduce l'insieme dei blocchi potenzialmente validi.



#### Separazione (Split)

Una biforcazione di una [Moneta](#moneta).



#### Riorganizzazione

Un [Annuncio](#annuncio) che promuove un [Ramo Debole](#ramo-debole-weak-branch) sulla [Catena](#catena).

> Reorg è una abbreviazione di questo termine.



#### Stallo

L'assenza di incremento di [Altezza](#altezza-height) nel tempo.



#### Attivazione

Iniziare ad [Applicare](#applicazione-delle-regole-enforcement) una nuova [Regola](#regola).



#### Segnalazione (Signal)

Una indicazione di un [Miner](#miner) veicolata dai dati di un [Blocco](#blocco) relativa all'intenzione di [Applicare](#applicazione-delle-regole-enforcement) una nuova [Regola](#regola). 



## Privacy



#### Identità

I modi di associare una [Comunicazione](#comunicazione) ad una [Persona](#persona).



#### Tracciamento (Taint)

Determinazione della [Proprietà](#proprietario).



## Sicurezza



#### Potere 

Il livello relativo di controllo di una [Persona](#persona) su una [Catena](#catena) o una [Moneta](#moneta).



#### Economia

L'insieme di tutti i [Commercianti](#commerciante).



#### Potere Economico

Una frazione di tutte le proprietà offerte in [Scambio](#scambio-di-unità).



#### Hash Power

Una frazione dell'[Hash Rate](#hash-rate) di tutti i [Centri di Mining](#centro-di-mining-mine).



#### Attacco 

Utilizzo di [Hash Power](#hash-power) al fine di realizzare una [Doppia Spesa](#doppia-spesa).

> Impedire una conferma è un modo per consentire una doppia spesa.



#### Cooptazione (Co-option)

Ricorso all'aggressione al fine di controllare dell'[Hash Power](#hash-power).



#### Coercizione

Ricorso all'aggressione al fine di indurre una [Attivazione](#attivazione).



#### Distorsione

Aggressione al [Mercato](#mercatop) che altera il costo del [Mining]().



#### Variazione

Differenze nel costo della risorsa per il [Mining](#centro-di-mining-mine).



#### Censura

[Conferma](#conferma) soggettiva.



#### Stato

Insieme di [Persone](#persona) che utilizzano l'aggressione al posto dello [Scambio](#scambio).

> Opera tipicamente in un regime di impunità all'interno di limiti geografici.



#### Politico

Che concerne le azioni degli [Stati](#stato).



## Debolezza



#### Aggregazione

La Tendenza alla ridotta partecipazione nel [Mining](centro-di-mining-mine) o nella [Validazione](#validità).

> Implica il raggruppamento o la centralizzazione.



#### Raggruppamento (Pooling)

La tendenza verso l'esistenza di pochi [Miner](#miner), che include il consolidamento dei [Relay](#propagatore-relay).

> Collusione è un comune sinonimo per questo termine.



#### Centralizzazione

La tendenza verso l'esistenza di pochi [Commercianti](#commerciante).

> I Commercianti controllano direttamente la validazione.



#### Delegazione

La tendenza verso l'esistenza di pochi [Proprietari](#proprietario).

> I Proprietari controllano direttamente la spesa.



#### Partizionamento

La tendenza verso [Partizioni](#partizione) persistenti.

> L'identità implica l'esclusione.



#### Correlazione

L'abilità di [Tracciare](#tracciamento-taint) usando metodi statistici di analisi della [catena](#catena) (_chain analysis_).































