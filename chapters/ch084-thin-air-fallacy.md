# Fallacia della Creazione dal Nulla



Esiste una teoria secondo la quale un [sistema bancario a riserva frazionaria]() dia intrinsecamente la capacità alle banche di creare moneta senza alcun costo reale. La teoria non dipende dal [privilegio di stato]() del [signoraggio](). Essa è considerata altresì come conseguenza del [_free banking_](). Talvolta ci si riferisce ad essa come creazione di moneta _ex nihilo_ o "dal nulla".

> Lord Adair Turner, già a capo della autorità di vigilanza finanziaria del Regno Unito, ebbe a dire: "Le banche, contrariamente a quanto affermano fin troppi libri di testo, non prendono i depositi monetari dai depositanti e li danno in prestito ai soggetti richiedenti: esse creano il credito e la moneta _ex nihilo_ - accendendo il prestito e contemporaneamente accreditando moneta sul conto del debitore."

I seguaci della teoria descrivono due visioni sulla creazione della moneta in competizione tra loro. La visione tradizionale è ritenuta semplice rispetto alla rappresentazione più pratica, come è implicato dalle parole di Lord Turner. La teoria afferma che il sistema bancario crei intrinsecamente non solo il credito, ma anche la moneta.

##### Visione Semplice

La moneta è creata dai [minatori]() ad un costo reale, viene venduta alle [persone](), e infine [data in prestito]() ad altre persone. La teoria ritiene che il prestatore sta dando in prestito solo il denaro in suo [possesso](). Come tale il prestatore sta operando a [riserva intera]() e non può mettere in pratica operazioni a riserva frazionaria che sono considerate fraudolente. Un prestatore onesto può solo emettere dei titoli ([moneta rappresentativa]()) contro moneta in suo possesso, impedendo l'espansione del credito e quindi una perdurante [inflazione dei prezzi]().

##### Visione Pratica

 I sostituti monetari vengono creati dalle banche, senza sostenere alcun costo reale e come conseguenza della riserva frazionaria. L'offerta di questi sostituti si espande ad ogni prestito e si contrae quando il prestito si [estingue](). Poiché è implicata la mancanza di vincoli sull'espansione del credito, il debito complessivo cresce senza limiti creando una perdurante inflazione dei prezzi.

In un libero mercato le persone possono svolgere le stesse operazioni delle banche, senza necessariamente chiamarsi banche. Di conseguenza la distinzione tra queste due possibilità deve basarsi sul modo con cui viene celata una supposta frode. La teoria sostiene che questo oscuramento è raggiunto usando un trucco contabile che non viene compreso in maniera diffusa. Allora proponiamoci di analizzare in profondità questa differenza. Ogni tipo di moneta risulterà sufficiente per condurre questa ricerca sui [sostituti monetari]() creati sopra ad essa e che includono Oro, Bitcoin o [moneta di monopolio]().

Nella visione ingenua, il potenziale prestatore ha risparmiato sia la liquidità necessaria per il suo consumo personale (accumulo) e l'ammontare destinato per ricavare un [interesse]() (investimento). In questo scenario tutta l'attività di prestito deriva dai risparmi, come ad esempio l'oro accumulato al [setaccio](). I risparmi includono la somma accumulata (denaro) ed il quantitativo di crediti in eccesso sui debiti: ` risparmi = denaro + (credito - debito)`. Il denaro è l'oro e i crediti sono sostituti monetari:

|         | risparmi | moneta | credito | debito |
| ------- | -------- | ------ | ------- | ------ |
| Persona | 100 oz   | 100 oz |         |        |

In questa visione del prestito personale, la Persona cede 81 once d'oro (oz) al Debitore. Il Debitore accetta l'obbligo di ripagare la Persona assieme ad un interesse alla scadenza del [prestito](). Per semplificare la contabilità assumeremo che vi sia interesse nullo e non si tenga in conto (i.e si sconti) del rischio di controparte:

|          | risparmi | moneta | credito | debito |
| -------- | -------- | ------ | ------- | ------ |
| Persona  | 100 oz   | 19 oz  | 81 oz   |        |
| Debitore |          | 81 oz  |         | 81 oz  |

La Persona ha dato in realtà in prestito alla sua stessa attività (e.g. un'attività di prestito) una frazione dei suo risparmi, di cui è tenuto conto di seguito. Assumiamo che che la Persona tenga da parte (accumuli) il 10% dei suo risparmi per far fronte alla liquidità necessaria ai consumi di breve termine e che l'Attività accumuli il 10% per la stessa ragione:

|          | risparmi | moneta | credito | debito |
| -------- | -------- | ------ | ------- | ------ |
| Persona  | 100 oz   | 10 oz  | 90 oz   |        |
| Attività |          | 9 oz   | 81 oz   | 90 oz  |
| Debitore |          | 81 oz  |         | 81 oz  |

L'Attività della persona sta operando con una riserva del 10% in quanto il 90% dei suoi risparmi a rischio di default. Applicare questo schema sulla visione semplice del sistema bancario richiede solamente si sostituire "Prestatore [Persona]" con "Depositante" e "Attività" con "Banca". Non vi è necessità di assumere che questi siano individui distinti:

|             | risparmi | moneta | credito | debito |
| ----------- | -------- | ------ | ------- | ------ |
| Depositante | 100 oz   | 10 oz  | 90 oz   |        |
| Banca       |          | 9 oz   | 81 oz   | 90 oz  |
| Debitore    |          | 81 oz  |         | 81 oz  |

Rappresentando correttamente la Persona come un soggetto avente avente denaro a rischio (i.e il depositante) possiamo vedere che tutta l'attività di prestito è a riserva frazionaria. In questo scenario dove la riserva è al 10% ci sono due prestiti che danno luogo a sostituti monetari (credito) pari al 171% della moneta sottostante. Data l'assunzione di una [preferenza temporale]() uniforme il Debitore darà in prestito il 10% dei suoi risparmi, come tutti i debitori successivi. Assumendo un prestito minimo pari ad 1 oncia, dopo 43 prestiti l'espansione del credito termina   con 8.903 volte il valore del denaro sottostante.

Sia `r`il livello uniforme delle riserve individuali e `m` la quantità di moneta, l'ammontare totale del credito `c` per ogni dato numero di prestiti `n` è dato dalla seguente [somma parziale]():

```
c = ∑(n=1..n)[m * (1 - r)^n] =
(m * (r - 1) ((1 - r)^n - 1))/r =
(100 oz * (10% - 1) ((1 - 10%)^43 - 1))/10% = 890.3 oz
```

Il rapporto di riserva `rr` è dato dal rapporto tra moneta e credito:

```
rr = m/c = 100 oz / 890.3 oz = ~11.23%
```

Il [moltiplicatore monetario]() è dato dall'inverso del rapporto di riserva:

```
1/rr = 1/(100oz/890.3oz) = 8.903
```

| Prestito | Accumulo | Prestito | Credito |
| -------- | -------- | -------- | ------- |
| 1        | 10.00    | 90.00    | 90.00   |
| 2        | 19.00    | 81.00    | 171.00  |
| 3        | 27.10    | 72.90    | 243.90  |
| 4        | 34.39    | 65.61    | 309.51  |
| 5        | 40.95    | 59.05    | 368.56  |
| 6        | 46.86    | 53.14    | 421.70  |
| 7        | 52.17    | 47.83    | 469.53  |
| 8        | 56.95    | 43.05    | 512.58  |
| 9        | 61.26    | 38.74    | 551.32  |
| 10       | 65.13    | 34.87    | 586.19  |
| 11       | 68.62    | 31.38    | 617.57  |
| 12       | 71.76    | 28.24    | 645.81  |
| 13       | 74.58    | 25.42    | 671.23  |
| 14       | 77.12    | 22.88    | 694.11  |
| 15       | 79.41    | 20.59    | 714.70  |
| 16       | 81.47    | 18.53    | 733.23  |
| 17       | 83.32    | 16.68    | 749.91  |
| 18       | 84.99    | 15.01    | 764.91  |
| 19       | 86.49    | 13.51    | 778.42  |
| 20       | 87.84    | 12.16    | 790.58  |
| 21       | 89.06    | 10.94    | 801.52  |
| 22       | 90.15    | 9.85     | 811.37  |
| 23       | 91.14    | 8.86     | 820.23  |
| 24       | 92.02    | 7.98     | 828.21  |
| 25       | 92.82    | 7.18     | 835.39  |
| 26       | 93.54    | 6.46     | 841.85  |
| 27       | 94.19    | 5.81     | 847.67  |
| 28       | 94.77    | 5.23     | 852.90  |
| 29       | 95.29    | 4.71     | 857.61  |
| 30       | 95.76    | 4.24     | 861.85  |
| 31       | 96.18    | 3.82     | 865.66  |
| 32       | 96.57    | 3.43     | 869.10  |
| 33       | 96.91    | 3.09     | 872.19  |
| 34       | 97.22    | 2.78     | 874.97  |
| 35       | 97.50    | 2.50     | 877.47  |
| 36       | 97.75    | 2.25     | 879.72  |
| 37       | 97.97    | 2.03     | 881.75  |
| 38       | 98.18    | 1.82     | 883.58  |
| 39       | 98.36    | 1.64     | 885.22  |
| 40       | 98.52    | 1.48     | 886.70  |
| 41       | 98.67    | 1.33     | 888.03  |
| 42       | 98.80    | 1.20     | 889.22  |
| 43       | 98.92    | 1.08     | 890.30  |

Si noti che, in condizione di espansione completa, affinché una persona spenda il proprio denaro accumulato mantenendo la propria preferenza temporale, un prestito deve essere estinto in modo da compensare la spesa. Il processo di estinzione [finalizzazione] del prestito muove il denaro dal primo debitore al suo creditore, e da luogo alla cancellazione della nota di debito. La persona che riceverà le monete derivanti dalla spesa le darà necessariamente in prestito per soddisfare la sua preferenza temporale e così via.

Non è possibile alcuna ulteriore espansione senza l'incremento della quantità di moneta o di una riduzione complessiva della preferenza temporale. Un incremento della moneta incrementa il quantitativo assoluto di credito disponibile e una riduzione della preferenza temporale incrementa la proporzione di credito rispetto alla moneta. Poiché moneta e credito evolvono assieme, non vi è mai un incremento reale di sostituti monetari tranne che derivante da questi cambiamenti.

Nella tipica pratica della contabilità bancaria la Banca non cede il denaro [al termine del prestito]. Al suo posto essa crea delle voci contabili in un processo al quale ci si riferisce con il nome di "creazione del credito". Il processo crea delle voci di [libro contabile]() che si compensano tra i ricavi e i prestiti del Depositante ("credito" e "debito") e delle voci che si compensano dello [stato patrimoniale]() della banca stessa ("attività" e "passività" ). All'emissione del prestito, i conti appaiono come indicato di seguito:

|             | risparmi | moneta | credito | debito | attività [asset] | passività [liability] |
| ----------- | -------- | ------ | ------- | ------ | ---------------- | --------------------- |
| Depositante | 100 oz   | 10 oz  | 90 oz   |        | 100 oz           |                       |
| Banca       |          | 90 oz  | 81 oz   | 171 oz | 171 oz           | 171 oz                |
| Debitore    |          |        | 81 oz   | 81 oz  | 81 oz            | 81 oz                 |

A questo punto [le spiegazioni che è in grado di fornire la teoria]() tendono a cessare. Le partite di compensazione sia della Banca che del Debitore si controbilanciano, ma il Debitore ha a disposizione 81 once d'oro da spendere, e la Banca non ha avuto necessità di cedere alcun oro al Debitore. Ci sono sempre 100 once in moneta, ma il Debitore ha 81 once di sostituto monetario e la Banca ha 81 once d'oro in più di attività [asset]. La teoria afferma che quindi la Banca ha creato non solo credito, ma anche _moneta_. Si noti che tutto il quadro contabile è ancora bilanciato e tutti i conti possono essere finalizzati, e ciò sembrerebbe dare ragione alla teoria per come esposta da Lord Turner:

>"...esse creano il credito e la moneta _ex nihilo_ - accendendo il prestito e contemporaneamente accreditando moneta sul conto del debitore."

Questo tuttavia dimostra che nessuna spesa reale è stata ancora effettuata a partire dal credito del prestito o dall'asset della banca. Spingiamoci ancora leggermente oltre nel ragionamento assumendo che il Debitore proceda alla finalizzazione del suo conto [clearing] e di conseguenza finalizzi le corrispondenti attività e passività della Banca.

|             | risparmi | moneta | credito | debito | attività [asset] | passività [liability] |
| ----------- | -------- | ------ | ------- | ------ | ---------------- | --------------------- |
| Depositante | 100 oz   | 10 oz  | 90 oz   |        | 100 oz           |                       |
| Banca       |          | 90 oz  | 81 oz   | 90 oz  | 90 oz            | 90 oz                 |
| Debitore    |          | 81 oz  |         | 81 oz  | 81 oz            | 81 oz                 |

Si noti che questo è un esito identico a quello della visione semplice. **Non vi è distinzione tra queste due visioni apparentemente in competizione sulla creazione di moneta**, invalidando la teoria. Questo fatto risolve la [questione di durata secolare]() , cominciata apparentemente tra [Platone]() e [Aristotele](), che si domandava se la moneta fosse basata sull'attività estrattiva o sul credito. Le teorie sono identiche, in quanto la moneta ed il credito sono [duali]().

> Secondo Joseph Schumpeter, il primo seguace conosciuto della teoria del credito fu Platone. Schumpeter descrive il metallismo come l'altra teoria "delle due fondamentali teorie della moneta", aggiungendo che il primo seguace della teoria del metallismo fu Aristotele.

I seguaci delle due teorie stanno parlando semplicemente della [stessa cosa](). Bitcoin, così come la moneta fiat (i.e. una moneta che non ha [valore d'uso]()) in [assenza del supporto dello stato](), ha finalmente reso evidente sia gli errori logici del [metallismo](), che [provava a mostrare]() la necessità di una moneta con valore d'uso, che quelli del [cartalismo]() che [provavano a mostrare]() la necessità del supporto dello stato alla moneta fiat.

Si deve ricordare che ogni prestito ha una riserva del 10%, così la banca può dare in prestito fino a 8.903 volte l'ammontare di moneta a riserva, ovvero 890.30 once di sostituti monetari contro le 100 once di moneta a riserva. Se la Banca ha una riserva del 0% per ogni prestito, l'espansione del credito sarebbe infinita. Tuttavia questo implica una preferenza temporale pari a zero, equivalente all'idea che il tempo non abbia valore, cosa che implica che tutto il denaro viene imprestato indefinitamente. Nel caso della Banca, lo 0% in riserva implica che non vi sia alcuna liquidità per soddisfare alcun prelievo (i.e. la bancarotta immediata). Tuttavia, assumendo una preferenza temporale nulla non potrebbe mai esservi alcun prelievo rendendo lo scenario non rilevante ai fini pratici. L'espansione del credito è necessariamente finita.

Torniamo ora ad analizzare lo scenario dove la Banca crea del credito con una riserva negativa (i.e dal nulla), considerando questa volta una spesa. Ad esempio, su un deposito di 0 once la Banca ha intenzione di accendere un prestito di 1000 once. Al osto di basarsi sulla moneta a riserva per riuscire alla fine a finalizzare il prestito, la Banca "crea moneta" sul suo stato patrimoniale. La banca quindi procede a creare i conti di credito e debito intestati al debitore che rappresentano rispettivamente la moneta presa a prestito e l'obbligo di ripagare il prestito:



|          | risparmi | moneta | credito | debito  | attività [asset] | passività [liability] |
| -------- | -------- | ------ | ------- | ------- | ---------------- | --------------------- |
| Banca    |          |        | 1000 oz | 1000 oz | 1000 oz          | 1000 oz               |
| Debitore |          |        | 1000 oz | 1000 oz | 1000 oz          | 1000 oz               |

Quando il prestatore scambia 1 oncia d'oro (dal suo conto di credito) in cambio di una macchina, il suo conto viene diminuito di 1 oncia e quello del commerciante è incrementato di 1 oncia. Si noti che il Debitore ora deve alla banca 1 oncia che è stata anticipata dall'accordo del prestito.

|              | risparmi | moneta | credito | debito  | attività [asset] | passività [liability] |
| ------------ | -------- | ------ | ------- | ------- | ---------------- | --------------------- |
| Banca        |          |        | 1000 oz | 1000 oz | 1000 oz          | 1000 oz               |
| Debitore     | -1 oz    |        | 999 oz  | 1000 oz | 999 oz           | 1000 oz               |
| Commerciante | 1 oz     |        | 1 oz    |         | 1 oz             |                       |

Tutto sembra procedere bene finché il commerciante non prova a ritirare dal suo conto. A questo punto la Banca è in default e il Commerciante non può essere pagato. Se il conto del commerciante è con un'altra banca, il pagamento fallisce quando le due banche procedono a fare il _settlment_ dei conti. Con una ipotetica riserva negativa, i conti si bilanciano nel seguente modo, implicando che la Banca è in [fallimento]() (moneta negativa):

|              | risparmi | moneta | credito | debito  | attività [asset] | passività [liability] |
| ------------ | -------- | ------ | ------- | ------- | ---------------- | --------------------- |
| Banca        | -1 oz    | -1oz   | 1000 oz | 999 oz  | 999 oz           | 999 oz                |
| Debitore     |          |        | 999 oz  | 1000 oz | 999 oz           | 1000 oz               |
| Commerciante | 1 oz     | 1 oz   |         |         | 1 oz             |                       |

La moneta deve essere realmente [spostata]() dal controllo della Banca al Commerciante o alla Banca del Commerciante, cosa che non è possibile. Un esempio più semplice di ciò che accadrebbe è l'impossibilità da parte del Debitore di [prelevare]() dal suo conto. Le Banche possono tutta la quantità di sostituti monetari che desiderano, ma le riserve negative rappresentano solamente una [mancata promessa](). In questo esempio la banca ha creato 1000 once di promesse che non può mantenere.

Il non comprendere questi principi deriva probabilmente dal [non conoscere il funzionamento del processo di _settlement_](). E questo probabilmente deriva dal non riconoscere la intrinseca _dualità della moneta e del credito_, in quanto il primo deve necessariamente esistere per finalizzare i titoli di credito implicati dal secondo. E ciò probabilmente deriva dall'abitudine di riferirsi alla moneta (e.g l'oro) negli stessi termini con cui ci si riferisce ai sostituti monetari (e.g. crediti di oro).

Le voci contabili che si compensano di attività e passività sono servite solamente per rendere conto dei prestiti emessi ed in sospeso, cosa che sta alla base dello stato patrimoniale della Banca. In maniera simile la Banca non ha creato le voci che si compensano di credito e debito per mascherare la creazione fraudolenta di moneta. La Banca ha creato questi conti per due ragioni:

*  Precludere la possibilità di trasferimento fisico solo per ri-depositare il denaro nella Banca
* Incoraggiare il ri-deposito nella Banca a discapito dei concorrenti (o dell'accumulo da parte del Debitore).

Quando la Banca ha riserve insufficienti per soddisfare i prelievi, dovuti a prestiti in default o ad una [corsa agli sportelli](), ha solo due opzioni, andare in fallimento oppure chiedere un prestito. Per impedire il verificarsi della prima opzione è stato creato il [sistema bancario centrale]() atto a fornire la seconda opzione. Questo è il significato del termine "[prestatore di ultima istanza]()". Il [Principio della Banca di Stato]() fornisce una dettagliata spiegazione relativa alla reale fonte dell'[inflazione monetaria]().

In breve, è stato mostrato che:

* Le banche non hanno il potere di creare moneta.
* La riserva frazionaria è intrinseca all'attività di prestito.
* La quantità in riserva è una espressione della preferenza temporale.
* Una riserva nulla toglie ogni possibilità di essere in grado di effettuare il *settlement* dei conti.
* Non esiste alcuna distinzione tra la visione semplice e la visione pratica come teorie della creazione di moneta.