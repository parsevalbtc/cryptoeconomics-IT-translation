# Fallacia del Rendimento Risk Free



Il concetto ipotetico di [tasso di rendimento _risk free_](https://en.wikipedia.org/wiki/Risk-free_interest_rate) rappresenta il tasso di [interesse](ch101-glossary.md#interesse) economico ottenibile con un rendimento garantito sul [principale](https://www.investopedia.com/terms/p/principal.asp) del [prestito](ch101-glossary.md#dare-in-prestito---investire). Esiste una teoria secondo la quale Bitcoin ammetta nella pratica l'esistenza di tale rendimento attraverso l'imposizione della restituzione del principale. Un corollario di questa teoria afferma che questa proprietà consente anche di limitare l'[espansione del credito](ch046-credit-expansion-fallacy.md) in generale.

La teoria richiede l'esistenza dimostrabile di una garanzia ([_covenant_](https://en.wikipedia.org/wiki/Covenant_(law))) a scadenza temporale fissa sulle [unità](ch101-glossary.md#unità) della [moneta](ch101-glossary.md#moneta) date in prestito dal creditore. La garanzia assicura che il creditore non possa spendere le unità fino a quando il prestito non arrivi a [maturità](https://en.wikipedia.org/wiki/Maturity_(finance)) e che le unità tornino in possesso del creditore solo in quel momento. Il creditore scambia con il [debitore](ch101-glossary.md#prendere-a-prestito) queste unità bloccate in [cambio](ch101-glossary.md#scambio-di-unità) di un interesse. Il [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0) del prestatore imposto dalle unità bloccate dalla garanzia è compensato dall'interesse.

Tuttavia, le unità bloccate non forniscono alcuna utilità a colui che le ha prese in prestito. Il pieno controllo delle unità ritorna in maniera dimostrabile al prestatore, lasciando ogni [persona](ch101-glossary.md#persona) che le ha accettate con nulla in mano al momento del prestito. **Questo valore nullo è necessariamente attribuito ad ogni scambio precedente al termine del prestito e di conseguenza al prestito stesso, rendendo invalida la teoria**.


Esiste è una teoria collegata secondo la quale il costo opportunità del prestatore può essere usato per rappresentare una spesa dimostrabile, come avviene con la [_proof-of-work_](ch101-glossary.md#prova). Questo espediente può essere usato in maniera simile ad [hashcash](https://it.wikipedia.org/wiki/Hashcash), ovvero come un modo per mitigare il [_denial of service_](https://it.wikipedia.org/wiki/Denial_of_service). Ciò è vero, ma questo rappresenta una spesa e, come tale, essa può avverarsi solo spendendo unità (anche attraverso la loro distruzione). Così come nella *proof-of-work*, questo rappresenta uno scambio tra un costo dimostrabile di capitale e unità. Per questa ragione esso non costituisce un prestito (i.e. non dà luogo ad interesse), invalidando la teoria.

Esiste, inoltre, una teoria collegata secondo la quale le unità prese a prestito possono essere invece usate dal debitore per tracciare un asset di valore perpetuo. Poiché il tracciamento termina con la scadenza del prestito, la teoria è invalida per la stessa ragione.
In aggiunta, esiste una teoria collegata secondo la quale le unità prese a prestito possono essere usate per tracciare un asset a scadenza definita che termina alla scadenza del prestito (e.g. un biglietto del teatro). Ciò risulta possibile, tuttavia il costo di tracciamento, per qualsiasi durata, è limitato in BTC dalla [regola di consenso](ch101-glossary.md#regola) del limite di trasferimento ([_dust_](ch101-glossary.md#dust) limit) fissato ad una unità. Così il costo opportunità è limitato ad un'unità in aggiunta alle [commissioni](ch101-glossary.md#commissione-di-transazione-fee) di [transazione](ch101-glossary.md#transazione) necessarie per stabilire il prestito. 

L'[utilità](ch101-glossary.md#ch101-glossary.md#utilità) per il debitore è rappresentata dalla riduzione del costo di tracciamento per il tempo del prestito. Con un tasso di interesse del 10% e una scadenza superiore [approssimativamente a 7,2 anni](https://it.wikipedia.org/wiki/Regola_del_72s) diventa meno costoso spendere un'unità rispetto a prenderla in prestito. Spendendo immediatamente un'unità l'asset verrebbe tracciato indefinitamente.

Sebbene lo scenario economico finale di quanto appena proposto sia economicamente razionale, esso non può essere descritto accuratamente come un prestito, poiché le unità non possono essere né scambiate né distrutte dalla persona identificata come il destinatario del prestito. Sarebbe più appropriato riferirsi a questo costrutto come ad un "affitto" delle unità, per la sola ragione di distinguerlo da un vero prestito.

Ciònonostante, un rendimento può essere teoricamente ricavato sull'affitto di una unità, fino al limite economico imposto dal tasso di interesse (e.g. circa 7,2 anni al 10%). Tuttavia la commissione richiesta dall'operazione, per essere economicamente razionale, dovrebbero essere di 0 unità, in quanto è richiesta una transazione che dia avvio al prestito, cosa che non avviene quando vengono usate le proprie unità per fini di tracciamento. Così nel caso la domanda di transare ecceda l'offerta fissa di [conferma](ch101-glossary.md#conferma), questo scenario non è economicamente razionale. Questa relazione è valida per ogni valore del _dust limit_ maggiore di 0 nella misura in cui esso rappresenti una commissione insufficiente per finanziare la conferma.

---

Titolo originale: [Risk Free Return Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Risk-Free-Return-Fallacy)

[Indice](/README.md)

