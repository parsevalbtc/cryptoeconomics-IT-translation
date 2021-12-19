# Fallacia del _Selfish Mining_



Il termine [_selfish_](ch101-glossary.md#selfish-miner) [_mining_](ch101-glossary.md#centro-di-mining-mine) si riferisce a un'_ottimizzazione_ del mining. Tuttavia un [articolo accedemico](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf) inquadra tale ottimizzazione nel seguente modo:

> La convinzione comune afferma che il protocollo del mining è compatibile con gli incentivi economici ed è protetto dalla collusione di gruppi di minoranza, ovvero, esso incentiva i miner a seguire il protocollo come prescritto. Mostriamo qui che il protocollo di mining di Bitcoin non è compatibile con gli incentivi economici.
>
> *Ittay Eyal and Emin Gün Sirer: Majority is not Enough*

Questa affermazione presuppone che esista un "protocollo di mining di Bitcoin stabilito" che impedisca il [trattenimento](ch101-glossary.md#trattenimento-withholding), cosa che rappresenta una [argomentazione fallace](https://it.wikipedia.org/wiki/Argomento_fantoccio). Necessariamente, le [regole di consenso](ch101-glossary.md#regole-di-consenso) di Bitcoin non si esprimono su quale sia il tempo di attesa degli [annunci](ch101-glossary.md#annuncio).

>  Presentiamo qui un attacco con il quale i miner collusi ottengono un ricavo più grande rispetto a quella che sarebbe la loro giusta quota parte.

Questa affermazione assume che esista il concetto di "giusta quota parte" che è estraneo a Bitcoin e rappresenta un'altra argomentazione fallace. Un [miner](ch101-glossary.md#miner) è [ricompensato](ch101-glossary.md#ricompensa-reward) sulla base dei [blocchi](ch101-glossary.md#blocco) da lui trovati che raggiungono la [maturità](ch101-glossary.md#maturità), non sulla proporzione dell'[_hash rate_](ch101-glossary.md#hash-rate) corrente.

Questi argomenti fallaci vengono esplicitamente attribuiti alla "convinzione comune". In altre parole, l'articolo li utilizza per mostrare che la convinzione comune è scorretta. Tuttavia, l'articolo sbaglia a dichiarare in maniera incondizionata che questa _ingiusta violazione del protocollo_ costituisca un attacco:

> Questo attacco può avere conseguenze significative per Bitcoin: i miner razionali preferiranno unirsi ai _selfish miner_ ed il gruppo colluso aumenterà di dimensione finché non diventerà la maggioranza. A questo punto il sistema Bitcoin cessa di essere una valuta decentralizzata.

Questa è l'origine della fallacia. Non si tratta dell'attacco alla convinzione comune ad essere scorretto, ma l'errore sta nel dare per assodata la convinzione comune. Il _selfish mining_ implica che Bitcoin manifesta una pressione al [raggruppamento](ch101-glossary.md#raggruppamento-pooling) basata sulla [latenza](ch101-glossary.md#latenza), benché questo sia un [difetto ben conosciuto](ch036-proximity-premium-flaw.md). Tutte le pressione al raggruppamento tendono a ridurre il numero di miner, esponendo Bitcoin agli attacchi.

**Le ottimizzazioni non sono attacchi**. Il raggruppamento aumenta l'_opportunità_ degli attacchi, ma la sola opportunità non dovrebbe essere confusa con l'azione vera e propria. Il termine "[attacco](ch101-glossary.md#attacco)" implica il furto. Infatti, il [whitepaper di Bitcoin](https://bitcoin.org/bitcoin.pdf) usa questo termine solo per descrivere i tentativi di [doppia spesa](ch101-glossary.md#doppia-spesa).

---

Titolo originale: [Selfish Mining Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Selfish-Mining-Fallacy)

[Indice](/README.md)

