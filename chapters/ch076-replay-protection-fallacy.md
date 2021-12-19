# Fallacia della _Replay Protection_



Esiste una teoria secondo la quale la _replay protection_ applicata ad una [catena](ch101-glossary.md#catena) [separata](ch101-glossary.md#separazione-split) aumenti l'[utilità](ch101-glossary.md#utilità) relativa della catena originale. La _replay protection_ (n.d.t. protezione dalla ripetizione) è una [regola](ch101-glossary.md#regola) progettata in relazione ad un'altra catena e avente un comportamento direzionale. La protezione rende le [transazioni](ch101-glossary.md#transazione) della catena protetta [invalide](ch101-glossary.md#validità) sull'altra catena.

Anche senza protezione, è comunque possibile per un [possessore](ch101-glossary.md#proprietario) effettuare una [spesa](ch101-glossary.md#spesa) in una maniera tale da impedirne la ripetizione in una direzione o in un altra, sebbene questo porti ad un costo in termini di [_fee_](ch101-glossary.md#commissione-di-transazione-fee) e/o di complessità. Una separazione può ridurre ma non eliminare del tutto questo costo in una o entrambe le direzioni attraverso l'[attivazione](ch101-glossary.md#attivazione) di regole che possono essere utilizzate selettivamente dalle azioni di [spesa](ch101-glossary.md#spesa). Questo tipo di misura è chiamata _opt-in replay protection_ e si differenzia dalla _replay protection_ obbligatoria. La _opt-in replay protection_ riduce ma non elimina il costo mentre la protezione obbligatoria può eliminarlo.

La ripetizione di una spesa in un'altra catena è un'azione che non porta a [diluizione](https://en.wikipedia.org/wiki/Stock_dilution). L'[output](ch101-glossary.md#output) comune può essere speso su entrambe le catene con o senza ripetizione. **La sola distinzione fornita dalla protezione è che le spese possono essere _distinte_ su ciascuna catena senza alcun costo aggiuntivo per colui che effettua la spesa**. L'[offerta](ch101-glossary.md#offerta) in ciascuna catena rimane inalterata dall'utilizzo della protezione.

Si tratta di una sorprendente incomprensione quella di credere che una catena possa assorbire, in qualche modo, le transazioni dell'altra in un evento di separazione. Tutti gli output del [segmento](ch101-glossary.md#segmento) comune rimangono spendibili su entrambe le catene. La _replay protection_ permette solo di ridurre il costo di spendere tali output sulla catena protetta.

E' possibile assumere che la mancanza di protezione renda meno probabile per un possessore spendere sulla catena non protetta, limitando di conseguenza l'offerta e aumentando il [prezzo](ch101-glossary.md#prezzo) di [scambio](ch101-glossary.md#scambio-di-unità). Tuttavia questo presuppone che la domanda non sia influenzata da quello che si configura come un aumento del costo di [scambio](ch101-glossary.md#scambio). Se il possessore non sta effettuando scambi in quanto vi è un incremento di costo nel farlo, allora l'utilità della moneta non aumenta ma bensì diminuisce.

Il costo di proteggersi autonomamente consiste in un [demurrage](https://en.wikipedia.org/wiki/Demurrage_(currency)) _una tantum_ che rimane finché la protezione è applicata alle [unità](ch101-glossary.md#unità) non protette, in maniera intenzionale o altrimenti. Questo costo rappresenta uno [sconto](https://it.wikipedia.org/wiki/Valore_attuale_netto) sull'utilità di una catena non protetta se confrontata con la stessa ipotetica catena dotata di protezione. Questo implica una _maggiore_ utilità della catena protetta rispetto a quella non protetta - che si è formata a seguito della separazione - rispetto a quanto sarebbe avvenuto in condizioni differenti. Di conseguenza la teoria è invalida.

---

Titolo originale: [Replay Protection Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Replay-Protection-Fallacy)

[Indice](/README.md)

