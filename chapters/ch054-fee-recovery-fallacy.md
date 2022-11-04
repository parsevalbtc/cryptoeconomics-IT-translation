# Fallacia del Recupero della Commissione



Esiste una teoria secondo la quale i [miner](ch101-glossary.md#miner) ricavino un vantaggio finanziario su altri miner quando [minano](ch101-glossary.md#centro-di-mining-mine) le loro stesse transazioni e quindi "recuperano" le loro stesse [_fee_](ch101-glossary.md#commissione-di-transazione-fee).

La teoria ignora il [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0) di occupare lo spazio del [blocco](ch101-glossary.md#blocco) senza incassare un pagamento. Il pagamento di una _fee di importo qualsiasi_ verso sé stessi è un non-evento finanziario. Non incassare una _fee_ rappresenta un costo reale sull'importo a cui si è rinunciato, in quanto il costo del mining per quella porzione del blocco non viene ricompensato. **La commissione effettivamente pagata dal miner è il costo opportunità a cui si è rinunciato.** 

Data la natura di gioco [a somma zero](ch032-zero-sum-property.md) del mining questa disparità consente ai miner più razionali di aumentare il loro [_hash power_](ch101-glossary.md#hash-power) reinvestendo il loro più alto ritorno del capitale.


Vi è una teoria correlata secondo la quale gli strumenti di stima delle _fee_ possano essere ingannati nel raccomandare delle _fee_ più alte di quanto sia effettivamente necessario. Come mostrato nella [Fallacia della Commissione a Parte](ch081-side-fee-fallacy.md) questo implica sia una relazione tra il valore storico ed il valore futuro delle _fee_ - relazione che non esiste, sia che tutte le commissioni siano visibili _on-[chain](ch101-glossary.md#catena)_, circostanza altrettanto non verificabile.

---

Titolo originale: [Fee Recovery Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Fee-Recovery-Fallacy)

[Indice](/README.md)

