# Modello di Banca Pura


Il concetto di una Banca Pura può essere utile nel dimostrare il comportamento generale dell'[imprestare il denaro](ch101-glossary.md#dare-in-prestito---investire).

Una Banca Pura fornisce solamente i seguenti servizi:

* prende a prestito denaro (ha un debito con i creditori)

* dà in prestito denaro (vanta un credito nei confronti dei debitori)

* accumula denaro (detiene una riserva)


Le differenze essenziali con una banca reale sono:

* la mancanza di intervento dello stato (regime di _free banking_)

* nessun costo operativo (efficienza perfetta)


La banca è di proprietà dei suoi creditori in proporzione al credito posseduto da ciascuno di essi, cosa che avviene in ogni società. Esistono banche di primaria importanza che sono possedute dai loro correntisti, ad esempio [USAA](https://www.usaa.com/) e [Vanguard](https://investor.vanguard.com/), cosa che non rappresenta una distinzione rispetto ad una banca reale. Né una banca pura né una banca reale possiedono "capitale proprio" da imprestare, in quanto tutto il capitale è preso a prestito dagli investitori in una forma o in un'altra. L'obiettivo dei creditori è quello di massimizzare il loro ritorno sull'investimento. L'obiettivo dei debitori è quello di minimizzare le spese dovute all'[interesse](ch101-glossary.md#interesse).

I conti dei creditori sono dei [sostituti monetari](https://wiki.mises.org/wiki/Money_substitutes). Questo aspetto distingue la banca da un fondo di investimento. I sostituti monetari possono essere sia dei [depositi a vista](https://en.wikipedia.org/wiki/Demand_deposit) che dei [fondi monetari](https://en.wikipedia.org/wiki/Money_market_fund). La distinzione tra i due dipende dal modo con cui vengono trattate le riserve insufficienti (tasso di rendimento negativo), nel primo caso sulla base dell'[ordine di arrivo](https://it.wikipedia.org/wiki/Panico_bancario) (_first come, first served_), mentre nel secondo attraverso la "[rottura della parità con il dollaro](https://en.wikipedia.org/wiki/Money_market_fund#Breaking_the_buck)" (_breaking the buck_).

La mancanza dell'intervento di stato è assimilata al noto concetto di [_free banking_](https://it.wikipedia.org/wiki/Free_banking), dove non vi è [controllo statuario](https://it.wikipedia.org/wiki/Federal_Reserve_System), [assicurazionedi stato](https://www.fdic.gov/), [capitale a sconto](https://en.wikipedia.org/wiki/Discount_window), o [signoraggio](https://it.wikipedia.org/wiki/Signoraggio). La banca utilizza una [moneta commodity](ch005-money-taxonomy) se non specificato diversamente, cosa che semplifica i calcoli [eliminando](ch013-inflation-principle.md) il bisogno di compensare l'[inflazione](https://en.wikipedia.org/wiki/Inflation) o la [deflazione](https://en.wikipedia.org/wiki/Deflation) del prezzo.

Rispetto ad una banca reale, l'ipotesi di efficienza perfetta differisce solo nel tasso di ritorno, in quanto non viene consumato nulla in spese operative. Tutti i ricavi sono conseguenza della [preferenza temporale](ch085-time-preference-fallacy.md). Viene assunto un tasso di interesse uniforme, in quanto l['arbitraggio](https://it.wikipedia.org/wiki/Arbitraggio) tra tassi è una spesa. Il [_demurrage_](https://it.wikipedia.org/wiki/Demurrage_(moneta)) è definito come la spesa dovuta al deposito del denaro. Il rapporto di spesa (inclusivo del _demurrage_) è pari a 1 per la banca pura.

Il capitale [riservato](ch098-reserve-definition.md)  è il denaro con cui viene effetuato il [_settlement_](https://it.wikipedia.org/wiki/Regolamento_(finanza)) di crediti e debiti (tempo zero di [maturità](https://en.wikipedia.org/wiki/Maturity_(finance))). La [svalutazione](ch011-depreciation-principle.md) rappresenta il [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0) dello stesso capitale a non essere investito, anche noto come "_cash drag_". Si assume che le relazioni di interesse valgano per un singolo periodo di [interesse composto](https://it.wikipedia.org/wiki/Interesse#Interesse_composto), avente tasso fissato per quel periodo. Queste semplificazioni, per come sono state presentate, non hanno rilevanza per le relazioni implicate.

Data la precedente definizione di banca pura, le seguenti relazioni valgono in maniera assoluta.

```

[capitale] riservato     = preso-in-prestito - investito
demurrage     	         = tasso-di-demurrage * riservato
svalutazione 	         = tasso-di-interesse * riservato
interesse     	         = tasso-di-interesse * investito
ritorno       	         = rapporto-di-spesa * interesse
```

Per la Banca Pura, il [rapporto di riserva](https://en.wikipedia.org/wiki/Reserve_requirement) determina interamente il [rapporto di capitale](https://en.wikipedia.org/wiki/Capital_requirement), il [rapporto di debito](https://en.wikipedia.org/wiki/Debt_ratio), e il rapporto di risparmio.

##### Rapporto di Riserva

```
rapporto-di-riserva = riservato / preso-in-prestito
	            = (preso-in-prestito - investito) / preso-in-prestito
```



##### Rapporto di Capitale

```
rapporto-di-capitale = riservato / investito
		     = (preso-in-prestito - investito) / investito
```



##### Rapporto di Debito

```
rapporto-di-debito = preso-in-prestito / riservato
	           = preso-in-prestito / (preso-in-prestito - investito) 
```


##### Rapporto di Risparmio

```
rapporto-di-risparmio = investito / riservato 
		      = investito / (preso-in-prestito - investito) 
```


##### Stato Patrimoniale

La Banca Pura non ha fonti di indebitamento ma solamente capitale sociale (_equity_) apportato dagli azionisti.

| Asset della banca - Attività | Capitale Sociale - Passività |
| ---------------------------- | ---------------------------- |
|    investito + riservato     |      preso-in-prestito       |


##### Tasso di Rendimento

Il tasso di rendimento del creditore (ritorno) è, in aggiunta, una funzione del tasso di interesse. Il tasso di rendimento del creditore è inferiore al tasso di interesse del debitore a causa del _cash drag_, la spesa necessaria per sostenere la domanda di prelievo. Per ridurre queste spese sono tipicamente inclusi dei vincoli temporali nei [contratti delle banche reali](https://www.chase.com/content/dam/chasecom/en/checking/documents/deposit_account_agreement.pdf). Ad esempio, per legge, ogni prelievo da un conto corrente con interesse degli Stati Uniti può essere ritardato di 7 giorni. Il creditore può eliminare il [_cash drag_](https://www.investopedia.com/terms/p/performance_drag.asp) tenendo il debito in un fondo di investimento (i.e. senza assicurazioni sul _settlement_).

```
tasso-di-rendimento = tasso-di-interesse * (investito / preso-in-prestito)
```

Come mostrato nella [Relazione del Risparmio](ch091-saving-relation.md) il rapporto di capitale individuale determina completamente il tasso di interesse del [mercato](ch101-glossary.md#mercato). Quando si considera che ogni persona operi come una banca pura, risulta chiaro che il rapporto di capitale determina il tasso di interesse. Un rapporto di capitale dello 0% per tutte le persone implica che il capitale è gratuito e non ha rendimento. Con rapporti di capitale via via crescenti il tasso di interesse cresce in maniera concorde. Con un accumulo totale il costo del capitale è "infinito" - nessuna parte di esso può essere impiegata nella produzione.

L'assunzione della [relazione monetaria](ch013-inflation-principle.md) è che il prezzo sia proporzionale al rapporto della domanda rispetto all'offerta. Tuttavia, come mostrato nella Relazione del Risparmio, offerta e domanda di capitale esistono in una relazione a somma zero. Un incremento nell'[accumulo](ch101-glossary.md#accumulare) implica una corrispondente diminuzione nel dare in prestito e l'opposto implica un aumento. Per questa ragione, né il rapporto di capitale né il tasso di interesse sono grandezze lineari in rapporto alle variazioni dell'ammontare accumulato (o dato in prestito). Questo fenomeno ha portato alla ricerca di un "[rapporto aureo](https://en.wikipedia.org/wiki/Golden_Rule_savings_rate)" per queste grandezze. Tuttavia, data la soggettività del valore, ciò si rivela sostanzialmente un esercizio inutile.

Tuttavia, i rapporti di capitale determinano il tasso di interesse. Poiché tutte le persone, individualmente, provano ad ottenere un rapporto aureo basato sulle loro preferenze, il tasso di interesse del mercato deriva da queste ultime. Sostituendo il rapporto di capitale al tasso di interesse viene dimostrato l'effetto della riserva sulla Banca Pura, sotto l'ulteriore assunzione che ognuno operi come una Banca Pura e con lo stesso rapporto di capitale. Il rapporto di capitale include la svalutazione dei beni presenti, che nel caso della moneta è rappresentata dal *demurrage*. Il rapporto di *demurrage* della Banca Pura è pari a 1, così tale termine si semplifica.

```
tasso-di-rendimento = (riservato * demurrage / investito) * (investito / preso-in-prestito)
		    = (riservato / preso-in-prestito) * demurrage
		    = riservato / presto-in-prestito
```

Il tasso di ritorno sull'investimento per una Banca Pura diventa così il rapporto di riserva. Ciò non implica che una singola Banca Pura possa fissare il suo ritorno fissando il suo rapporto di capitale. Ciò riflette semplicemente il fatto che il rapporto di mercato del capitale determina il ritorno sul capitale. Se *tutti i prestatori* raddoppiassero il loro attuale rapporto di capitale il loro ritorno raddoppierebbe necessariamente, poiché il costo per il capitale, e quindi il suo rendimento, raddoppierebbe. 


##### Le Banche Reali

I rapporti di capitale stabiliti indipendentemente dalle persone, basati sulla preferenza temporale, determinano il tasso di interesse di mercato. La sostituzione apportata qui sopra per il rapporto di capitale proprio della banca come tasso di interesse, sembra implicare che la banca stia fissando il tasso di interesse. Tuttavia, questo è connaturato al concetto di preferenza temporale. Una banca può fissare il tasso di interesse che preferisce. Non vi è alcuna assunzione che il mercato possa imporre su questo aspetto, di conseguenza vengono assunti l'interesse e quindi il rendimento di mercato. 

```
tasso-di-rendimento-di-mercato = tasso-di-interesse-di-mercato * (investito / preso-in-prestito)
                               = rapporto-di-capitale-di-mercato * (investito / preso-in-prestito) 
```

La banca in regime di _free banking_ differisce dalla Banca Pura anche per quanto riguarda le spese operative che riducono direttamente il tasso di rendimento.

```
tasso-di-rendimento-free-banking = tasso-di-rendimento-di-mercato * rapporto-di-spesa
```

A sua volta, la Banca Reale differisce dalla banca in regime di _free banking_ per quanto riguarda la tassazione (inclusiva delle spese regolatorie) che riduce direttamente il tasso di rendimento.

```
tasso-di-rendimento-reale = tasso-di-rendimento-free-banking * rapporto-di-tassazione
```

A sua volta, la Banca Centrale (di stato) differisce dalla banca reale per quanto riguarda il sussidio fornito dai contribuenti (inclusivo dello sconto applicato ai prestiti ricevuti), cosa che incrementa il tasso di rendimento.

```
tasso-di-rendimento-banca-centrale = tasso-di-rendimento-reale * rapporto-di-sussidio-reddito
```

Ove la tassa includa il signoraggio sulla moneta impiegata dalla banca è necessario applicare l'[Equazione di Fisher](https://it.wikipedia.org/wiki/Equazione_di_Fisher_(economia)) alle relazioni precedenti per tradurre il tasso di interesse da un tasso nominale ad un tasso reale. Non vi è nessun’altra differenza oltre alla tassa, che è già stata inclusa nell'esempio della Banca Reale riportato sopra. Questa tassa è in generale la fonte del sussidio, di cui si è tenuto conto nell'esempio della Banca Centrale riportato sopra.

Ogni [persona](ch101-glossary.md#persona), o società di persone, è una Banca Reale e lo [stato](ch101-glossary.md#stato) è una Banca Centrale. Una Banca Reale garantisce il servizio di fornire liquidità agli investimenti, un [bene economico](https://en.wikipedia.org/wiki/Goods). Il costo di produzione è la svalutazione delle sue riserve. Questo rappresenta il modello di tutta la produzione.

-----------

Titolo orginale: [Pure Bank](https://github.com/libbitcoin/libbitcoin-system/wiki/Pure-Bank)  

[Indice](/README.md)


