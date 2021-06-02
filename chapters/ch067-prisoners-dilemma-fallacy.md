# Fallacia del Dilemma del Prigioniero



Esiste una teoria secondo la quale, ogni stato, individualmente, se messo di fronte alla scelta di unirsi ad una messa al bando di Bitcoin affronti un [dilemma del prigioniero](https://it.wikipedia.org/wiki/Dilemma_del_prigioniero). Una messa al bando significativa implica che uno o più stati (identificati come "prigioni") applicheranno delle [sanzioni economiche](https://www.cfr.org/backgrounder/what-are-economic-sanctions) (come minimo) ad altri stati (identificati come "prigionieri") che potrebbero potenzialmente adottare Bitcoin come [valuta di riserva](https://it.wikipedia.org/wiki/Valuta_di_riserva).

Assumiamo che i prigionieri che decidessero di adottare Bitcoin siano partner [commerciali](ch101-glossary.md#scambio). In altre parole, l'uso di Bitcoin come moneta di riserva necessità di un partner con cui [transare](ch101-glossary.md#transazione) commercialmente.

L'[utilità ordinale](https://en.wikipedia.org/wiki/Ordinal_utility) è implicata dal [valore soggettivo](https://en.wikipedia.org/wiki/Subjective_theory_of_value). Non sono previste situazioni di [parità](https://en.wikipedia.org/wiki/Tie_(draw)), cosa che implica un dilemma in senso forte. Nel seguito sono prese in considerazione sia la configurazione di conoscenza simmetrica che quella asimmetrica.

Il risultato per l'adozione individuale di Bitcoin (**S**tupido):

* Sanzioni economiche.
* Nessun partner commerciale (che utilizza il Dollaro).
* Una valuta di riserva inutilizzabile (nessun partner commerciale).

Il risultato per una mutua adozione di Bitcoin (**R**icompensa):

* Sanzioni economiche.
* Sanzioni economiche al partner commerciale.
* Una valuta di riserva non tassata attraverso il signoraggio.

Il risultato per un'adozione individuale del Dollaro (**T**entazione):

* Nessuna sanzione economica.
* Sanzioni economiche al partner commerciale.
* Una valuta di riserva tassata attraverso il signoraggio.

Il risultato per una mutua adozione del Dollaro  (**P**unizione):

* Nessuna sanzione economica.
* Nessuna sanzione economica al partner commerciale.
* Una valuta di riserva tassata attraverso il signoraggio.

 

##### Dilemma Simmetrico in forma Forte con Risultati in Relazione Ordinale

| Brasile/Irlanda | Bitcoin | Dollaro |
| --------------- | ------- | ------- |
| Bitcoin         | R\R     | S\T     |
| Dollaro         | T\S     | P\P     |

Per essere considerato un dilemma del prigioniero deve valere la relazione `T > R > P > S` dove:

* `T > R ` e `P > S` implicano che il Dollaro è la strategia dominante per ciascuno.
* `R > P`  implica che la mutua adozione di Bitcoin è preferita alla mutua adozione del Dollaro.

Possiamo concludere che valga  `P > S`  in quanto una sanzione economica individuale implica che non vi sia nessun _settlement_ internazionale e di conseguenza nessun beneficio dall'avere una [riserva estera](https://en.wikipedia.org/wiki/Foreign_exchange_reserves), e presumibilmente le sanzioni rappresentano una conseguenza non desiderabile.

Per determinare se valgano rispettivamente `R > P` e `T > R` risulta necessario impiegare un metodo oggettivo per confrontare il solo signoraggio con le sanzioni, in quanto le sanzioni rappresentano presumibilmente una conseguenza non desiderabile. Questa relazione d'ordine può essere ottenuta notando che l'oro non è soggetto né al [signoraggio](https://it.wikipedia.org/wiki/Signoraggio) né alle sanzioni. **In altre parole l'oro fornisce i benefici descritti in precedenza per Bitcoin senza le sanzioni**. Tuttavia l'oro non è stato scelto come valuta di riserva (ed è stato abbandonato in favore del Dollaro), il che implica che l'utilizzo del Dollaro è preferito a quello dell'oro e di conseguenza anche all'utilizzo di Bitcoin. Per questa ragione nessuna delle [strategie dominanti](https://en.wikipedia.org/wiki/Strategic_dominance) trova applicazione. Perciò non vi è alcun dilemma.



##### Dilemma [Asimmetrico](https://plato.stanford.edu/entries/prisoner-dilemma/#Asym) in forma Forte con Risultati in Relazione Ordinale

| Brasile/Irlanda | Bitcoin | Dollaro |
| --------------- | ------- | ------- |
| Bitcoin         | Rr\Rc   | Sr\Tc   |
| Dollaro         | Tr\Sc   | Pr\Pc   |

Per essere considerato un dilemma del prigioniero deve valere la relazione `Ti > Ri > Pi > Si` dove:

* `Tr > Rr` e `Pr > Sr`
* `Tc > Rc` e `Pc > Sc` 
* `Rr > Pr` e `Rc > Pc`

Se valgono tutte queste relazioni l'adozione individuale del Dollaro è preferita a Bitcoin e l'adozione mutua di Bitcoin è preferibile. Poiché queste relazioni sono le stesse valutate nello scenario simmetrico, non vi è alcun dilemma.



##### Altre assunzioni

La relazione tra oro e Bitcoin presume che i costi di [_clearing_](https://it.wikipedia.org/wiki/Compensazione_(finanza)), di trasporto dell'oro e di [conferma](ch101-glossary.md#conferma) di Bitcoin siano trascurabili nel contesto del _settlement_ internazionale. Il _clearing_ richiede movimentazioni periodiche relative alla compensazione della bilancia dei pagamenti tra gli stati.

> ... ogni correzione degli sbilanciamenti economici verrebbe accelerata e normalmente non risulterebbe necessario aspettare fino al punto in cui risulterebbe necessario movimentare importanti quantità d'oro tra un paese e l'altro
>
> [The Classical Gold Standard](https://www.gold.org/about-gold/history-of-gold/the-gold-standard)

Il Dollaro è stato preferito all'oro nonostante esso abbia peso simile, ingombro significativamente più grande, e che subisca l'applicazione del signoraggio. La relazione tra oro e Bitcoin presume che non vi sia alcuna distinzione tra i due in termini di volatilità e liquidità, sebbene l'oro [superi](https://coinweek.com/bullion-report/bitcoin-vs-gold-10-crystal-clear-comparisons/) oggettivamente Bitcoin in entrambi i campi. Poiché sia Bitcoin che l'oro sono [monete stabili](ch030-stability-property.md), non viene assunto alcun ritorno speculativo per entrambe. Si presume inoltre che altre proprietà monetarie relative all'oro, a Bitcoin e al Dollaro siano equivalenti o non rilevanti dal punto di vista di una valuta di riserva di stato.

---

Titolo originale: [Prisoner's Dilemma Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Prisoner's-Dilemma-Fallacy)

[Indice](/README.md)

