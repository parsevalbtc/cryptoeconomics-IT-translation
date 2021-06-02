# Fallacia del recupero della _fee_



Esiste una teoria secondo la quale i [miner](ch101-glossary.md#miner) ricavino un vantaggio finanziario su altri miner quando [minano](ch101-glossary.md#centro-di-mining-mine) le loro stesse transazioni e quindi "recuperano" le loro stesse [_fee_](ch101-glossary.md#commissione-di-transazione-fee).

La teoria ignora il [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0) di occupare lo spazio del [blocco](ch101-glossary.md#blocco) senza incassare un pagamento. Il pagamento di una _fee_ verso sé stessi è un non-evento finanziario. Non incassare una _fee_ rappresenta un costo reale sull'importo a cui si è rinunciato, in quanto il costo del mining per quella porzione del blocco non viene ricompensato. **Il risultato che si ottiene è un più basso ritorno sul capitale rispetto ai miner che vendono effettivamente il loro spazio del blocco**. Data la natura di gioco [a somma zero](ch032-zero-sum-property.md) del mining questa disparità consente ai miner più razionali di aumentare il loro [_hash power_](ch101-glossary.md#hash-power) reinvestendo il loro più alto ritorno del capitale.

Un volume più alto di transazione che competono per avere [conferme](ch101-glossary.md#conferma) implica un aumento del livello medio delle _fee_. Questo fatto influenza tutti i miner allo stesso modo, tuttavia un incremento del livello delle _fee_ dà luogo a maggiore competizione, non ad un incremento del tasso di ritorno sul capitale. Al contrario, tutti i miner risentono di una [ridotta utilità](ch030-stability-property.md) causata dall'aumento di domanda e di conseguenza dal livello delle _fee_ (che è stato finanziato completamente dai miner che non sono stati ricompensati). In altre parole la conseguenza è l'opposto di quella proposta, e ciò rende la teoria invalida.

Vi è una teoria correlata secondo la quale gli strumenti di stima delle _fee_ possano essere ingannati nel raccomandare delle _fee_ più alte di quanto sia effettivamente necessario. Come mostrato ne la [Fallacia della _Fee_ a Parte](ch081-side-fee-fallacy.md) questo implica sia una relazione tra il valore storico ed il valore futuro delle _fee_ - relazione che non esiste, sia che tutte le _fee_ siano visibili _on-[chain](ch101-glossary.md#catena)_, circostanza altrettanto non verificabile.

---

Titolo originale: [Fee Recovery Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Fee-Recovery-Fallacy)

[Indice](/README.md)

