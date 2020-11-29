# Modello di Banca Pura

Il concetto di una Banca Pura può essere utile nel dimostrare il comportamento generale dell'[imprestare il denaro]().



Una banca pura fornisce solamente i seguenti servizi:

* prende a prestito denato (ha un debito con i creditori)

* dà in prestito denaro (vanta un credito nei confronti dei dei debitori)

* accumula denaro (riserva)

  

Le differenze materiali con una banca reale sono:

* la mancanza di intervento dello stato (free banking)

* nessun costo operativo (efficienza perfetta)

  

La banca è di proprietà dei suoi creditori in proporzione al credito posseduto da ciascuno di essi, cosa che avviene in ogni società. Esistono banche di primaria importanza che sono possedute dai loro correntisti, ad esempio [USAA]() e [Vanguard](), cosa che non rappresenta una distinzione rispetto ad una banca reale. Né una banca pura né una banca reale possiedono "capitale proprio" da imprestare, in quanto tutto il capitale è preso a prestito dagli investitori in una forma o in un'altra. L'obiettivo dei creditori è quello di massimizzare il loro rendimento dell'investimento (ritorno). L'obiettivo dei debitori è quello di minimizzare le spese dovute all'[interesse]().

I conti dei creditori sono dei [sostituti monetari](). Questo aspetto distingue la banca da un fondo di investimento. I sostituti monetari possono essere sia dei [depositi a vista]() che dei [fondi monetari](). La distinzione tra i due dipende dal modo con cui vengono trattate le riserve insufficienti (tasso di rendimento negativo), nel primo caso sulla base dell'[ordine di arrivo]() (first come, first served), mentre nel secondo attraverso la "[rottura del dollaro]()" (breaking the buck).

La mancanza dell'intervento di stato è assimilata al comune concetto di [_free banking_](), dove non vi è [controllo statuario](), [assicurazione]() di stato, [finestre dei tassi di sconto](), o [signoraggio](). La banca utilizza una [moneta]() commodity se non specificato diversamente, cosa che semplifica i calcoli [eliminando]() il bisogno di controbilanciare [l'inflazione]() o la [deflazione]() di prezzo.

L'ipotesi di efficienza perfetta differisce, rispetto ad una banca reale, solo nel tasso di rendimento, in quanto nulla viene consumato come spese operative. Tutti i ricavi sono conseguenza della [preferenza temporale](). Viene assunto un tasso di interesse uniforme, in quanto l['arbitraggio]() tra tassi è una spesa. Il [_demurrage_]() è definito come la spesa dovuta al deposito del danaro. Il rapporto di spesa (inclusivo del _demurrage_) è pari 1 per la banca pura.

Il capitale [riservato]()  è il denaro con cui crediti e debiti vengono regolati (a tempo 0 di [maturità]()). Il [deprezzamento]() rappresenta il costo-opportunità dello stesso a non essere investito, anche noto come "cash drag". Le relazioni di interesse assumono un singolo periodo per l'interesse composto (avente tasso fissato per quel periodo). Queste semplificazioni, per come sono presentate, sono irrilevanti per le relazioni implicate.

Date le precedente definizione di banca pura, le seguenti relazioni sono assolute.

```

(capitale) riservato     = preso_in_prestito - dato_in_prestito (investito)
demurrage     			 = tasso_di_demurrage * riservato
deprezzamento 			 = tasso_di_interesse * riservato
interesse     			 = tasso_di_interesse * investito
ritorno       			 = rapporto_di_spesa * interesse
```

Per la banca pura, il [rapporto di riserva]() determina interamente il [rapporto di capitale](), [il rapporto di debito](), [il rapporto di risparmio](), [lo stato patrimoniale]() e il [tasso di rendimento]().



##### Rapporto di Riserva

```
rapporto_di_riserva = riservato / preso_in_prestito
				    = (preso_in_prestito - investito) /  preso_in_prestito
```



##### Rapporto di Capitale

```
rapporto_di_capitale = riservato / investito
					 = (preso_in_prestito - investito) /  investito
```



##### Rapporto di Debito

```
rapporto_di_debito = preso_in_prestito / riservato
				   = preso_in_prestito / (preso_in_prestito - investito) 
                   = 1 / rapporto_di_riserva
```



##### Rapporto di Risparmio

```
rapporto_di_risparmio = investito / riservato 
					 =  investito / (preso_in_prestito - investito) 
```



##### Stato Patrimoniale

La pura banca non ha fonti di indebitamento, ma solamente capitale sociale apportato dagli azionisti.

| Asset della banca - Attività | Capitale Sociale - Passività |
| :--------------------------: | :--------------------------: |
|    investito + riservato     |      preso_in_prestito       |

##### Tasso di Rendimento

Il tasso di rendimento di un creditore è, in aggiunta, una funzione del tasso di interesse. Il tasso di rendimento del creditore è inferiore di quello del debitore a causa del "cash drag", la spesa necessaria per sostenere la domanda di prelievo. Per ridurre queste spese sono tipicamente inclusi dei vincoli temporali nei [contratti della banca reale](). Ad esempio, per legge, ogni prelievo da un conto corrente con interesse degli Stati Uniti può essere ritardato di 7 giorni. Il creditore può eliminare il cash drag tenendo il debito in un fondo di investimento (i.e. senza assicurazioni sul settlement) in opposizione al debito tenuto in una banca.



```
tasso_di_rendimento = tasso_di_interesse * (investito / preso_in_prestito)
```



Come mostrato nelle [Relazioni del Risparmio]() il rapporto di capitale è il tasso di interesse. Il rapporto di capitale include il deprezzamento dei beni presenti, che nel caso della moneta è il _demurrage_. Il _demurrage_ della banca pura è 1, quindi questo termine scompare dall'espressione. Sostituendo il rapporto di capitale nella formula si ottiene il tasso di rendimento espresso nei termini del capitale preso a prestito ed investito.

```
tasso_di_rendimento = (riservato * demurrage / investito) * 								          (investito / preso_in_prestito)
					= (riservato /preso_in_prestito) * demurrage
					= riservato/ presto_in_prestito
```

 **Il tasso di rendimento di una banca pura è il rapporto di riserva.**

##### Le Banche Reali

I rapporti di capitale stabiliti indipendentemente dalle persone, basati sulla preferenza temporale, determinano il tasso di interesse di [mercato](). La sostituzione apportata qui sopra per il rapporto di capitale proprio della banca come tasso di interesse implica che la banca sta fissando il tasso di interesse. Tuttavia questo è connaturato al concetto di preferenza temporale. Una banca può fissare il tasso di interesse che preferisce. Non vi è assunzione per le banche reali di imposizione da parte del mercato, di conseguenza vengono assunti l'interesse e quindi il rendimento di mercato. 

```
tasso_di_rendimento_di_mercato = tasso_di_interesse_di_mercato *    
                                 (investito / preso_in_prestito)
                               = rapporto_di_capitale_di_mercato *										         (investito / preso_in_prestito) 
```

La banca in regime di _free banking_ differisce dalla banca pura anche per quanto riguarda le spese operative che riducono direttamente il tasso di rendimento.

```
tasso_di_rendimento_free_banking = tasso_di_rendimento_di_mercato * 									   rapporto_di_spesa
```

A sua volta, la banca reale differisce dalla banca in regime di _free banking_ per quanto riguarda la tassazione (inclusiva delle spese regolatorie), che riduce direttamente il tasso di rendimento.

```
tasso_di_rendimento_reale = tasso_di_rendimento_free_banking * 									    rapporto_di_tassazione
```

La banca centrale (di stato) differisce, a sua volta, dalla banca reale per quanto riguarda il sussidio fornito dai contribuenti (inclusivo dello sconto applicato ai prestiti ricevuti), cosa che incrementa il tasso di rendimento.

```
tasso_di_rendimento_centrale = tasso_di_rendimento_reale * 									           rapporto_di_sussidio_reddito
```

Ove la tassa includa il signoraggio sulla moneta impiegata dalla banca, l'[Equazione di Fisher]() deve essere applicata sulle relazioni precedenti per tradurre il tasso di interesse da una tasso nominale ad un tasso reale. Non vi è implicata alcuna altra variazione oltre alla tassa, che è già inclusa nell'esempio della banca reale riportato. Questa tassa è in generale la fonte del sussidio, che è già incluso nell'esempio della banca centrale riportato.

Ogni [persona](), o società di persone, è una banca reale, e lo [stato]() è una banca centrale. Una banca reale garantisce il servizio di fornire investimenti liquidi, un bene economico. Il costo di produzione è il deprezzamento delle sue riserve. Questo è il modello di tutta la produzione.