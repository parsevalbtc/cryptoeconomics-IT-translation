# Principi di Criptodinamica



Criptodinamica è un termine definito in questa raccolta con lo scopo di riferirsi facilmente ai principi fondamentali di [Bitcoin](ch101-glossary.md#bitcoin). Ciò è fatto con l'intento sia di sia di aiutare nella comprensione di Bitcoin sia di differenziarlo da altre tecnologie. Questi principi rappresentano il sottoinsieme minimo di principi _criptoeconomici_ necessari per raggiungere questo obiettivo.

Benché la scelta del nome non sia essenziale il razionale sottostante è fornito di seguito.

### Cripto

"Una criptovaluta è una [moneta] che impiega crittografia robusta per proteggere transazioni finanziarie, controllare la creazione di unità addizionali, e verificare il trasferimento [di unità]." - [Wikipedia](https://en.m.wikipedia.org/wiki/Cryptocurrency)

### Dinamica

"La dinamica è quella branca della matematica applicata [...] che si occupa dello studio delle forze [...] e del loro effetto sul moto." - [Wikipedia](https://en.wikipedia.org/wiki/Dynamics_(mechanics))

### Cripto + Dinamica

Criptodinamica è l'insieme delle forze che proteggono le [transazioni](ch101-glossary.md#transazione) Bitcoin controllando (1) la [definizione](ch101-glossary.md#validità) delle [unità](ch101-glossary.md#unità), e (2) il [trasferimento](ch101-glossary.md#conferma) delle unità.

### Principi

La forza delle sicurezza è interamente umana in natura. Le [persone ](ch101-glossary.md#persona)devono agire per proteggere qualsiasi cosa, incluso Bitcoin. Vista come sistema economico, la sicurezza di Bitcoin prevede che le persone agiscano in una maniera economicamente razionale (proprio interesse). Come tale, le forze di sicurezza di Bitcoin sono basate interamente sulle azioni di singoli individui a tutela del proprio interesse, specificamente:

* [Condivisione del Rischio](ch016-risk-sharing-principle.md)
* [Dissipazione di Energia](ch072-proof-of-stake-fallacy.md)
* [Bilanciamento del Potere](ch028-censorship-resistance-property.md)

Tali forze dipendono, in quest'ordine, l'una dall'altra. Senza condivisione dei rischi, l'energia non può essere spesa nel sistema per bilanciare il [potere](ch101-glossary.md#potere) di un entità [censurante](ch101-glossary.md#censura). Se queste tre forze rimangono integre Bitcoin può essere protetto. In mancanza di una sola di esse una tecnologia non può essere definita Bitcoin.

Data l'esistenza di queste tre forze, [non si può assumere](ch004-axiom-of-resistance.md) che una implementazione di Bitcoin possa essere protetta in senso assoluto. Inoltre, una implementazione potrebbe essere più sicura di un'altra. **L'unico criterio di distinzione è quello secondo cui una tecnologia è Bitcoin se include queste forze mentre non è Bitcoin se non le include**.

La possibilità di protezione permessa da queste forze si definisce "sicurezza criptodinamica". Così, ad esempio, una "blockchain _permissioned_" viola il principio di condivisione dei rischi, una tecnologia basata strettamente su proof-of-stake (PoS) viola il principio di dissipazione dell'energia e una moneta che si affida interamente alla componente di [sussidio](ch101-glossary.md#sussidio) per ricompensare la [conferma](ch101-glossary.md#conferma) delle transazioni viola il principio di bilanciamento del potere. Nessuno di questi esempi e criptodinamicamente sicuro.

---------
Titolo originale: [Cryptodynamic Principles](https://github.com/libbitcoin/libbitcoin-system/wiki/Cryptodynamic-Principles)
[Indice](/README.md)

