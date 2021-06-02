# Proprietà della Soglia di Utilità



L'[utilità](ch101-glossary.md#utilità) viene espressa come la preferenza di una [moneta](ch101-glossary.md#moneta) rispetto ai sostituti (n.d.t. monetari) per [trasferimenti](ch101-glossary.md#trasferimento) di [valore](ch101-glossary.md#valore) confrontabile. Un'utilità più elevata implica un livello di [_fee_](ch101-glossary.md#commissione-di-transazione-fee) più elevato, sotto l'ipotesi che vi sia un più elevato volume di [transazioni](ch101-glossary.md#transazione). La competizione per la [conferma](ch101-glossary.md#conferma) porta ad aumentare le _fee_. Poiché nel corso del tempo si assiste a delle differenze nel [mercato](ch101-glossary.md#mercato) del [prezzo](ch101-glossary.md#prezzo) delle _fee_, un individuo può offrire una _fee_ non competitiva nell'aspettativa di attendere un tempo più lungo per ottenere la conferma della sua transazione. Altri individui non transeranno sulla [catena](ch101-glossary.md#catena) affidandosi invece ai sostituti monetari.

La più elevata utilità, quindi, implica l'aumento del valore medio transato in quanto le _fee_ crescenti porterebbero il costo del trasferimento ad eccedere il valore trasferito. Una maggiore [profondità](ch101-glossary.md#profondità-depth) (n.d.t. delle transazioni "sepolte" dentro la catena) implica una maggiore sicurezza della conferma. Di conseguenza è possibile scambiare del tempo in cambio di una _maggiore_ sicurezza contro la [doppia spesa](ch101-glossary.md#doppia-spesa). Tuttavia, il tempo non può essere ridotto al di sotto del periodo di un blocco al fine di ottenere la più _bassa_ sicurezza possibile. I più bassi livelli di sicurezza sono rispettivamente: nessuna sicurezza (come transazione [non confermata](ch101-glossary.md#non-confermata)) e sicurezza minima (una conferma). Non può essere effettuato nessuno scambio tra questi due livelli.

_Fee_ più elevate implicano un [_hash rate_](ch101-glossary.md#hash-rate) più elevato, cosa che mitiga la necessita di aumentare la profondità di conferma per valori di trasferimento più elevati. **Poiché non vi è modo di ridurre la sicurezza per valori di trasferimento più piccoli, il più piccolo valore di trasferimento utile cresce assieme all'utilità**. Il mancato supporto ai trasferimenti in un certo intervallo di valori implica che i sostituti sono meno cari in quell'intervallo di valori. Questo implica la possibilità che coesistano differenti monete al fine di servire distinti intervalli di valore. Tuttavia tutti i tipi di Bitcoin (n.d.t intesi come sistemi di protocollo monetario analoghi - inclusivi dei più celebri fork) possiedono intrinsecamente questa proprietà.

Differenze nelle [regole](ch101-glossary.md#regola) in termini di periodo o dimensione dei [blocchi](ch101-glossary.md#blocco) non cambiano questa relazione. L'effetto di queste variazioni tra monete è strettamente proporzionale. Anche un sistema con blocchi di dimensione illimitata deve produrre dei livelli di _fee_ che portano fuori mercato i trasferimenti di basso valore. 

---

Titolo originale: [Utility Threshold Property](https://github.com/libbitcoin/libbitcoin-system/wiki/Utility-Threshold-Property)

[Indice](/README.md)

