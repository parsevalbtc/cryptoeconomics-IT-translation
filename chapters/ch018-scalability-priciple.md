# Principio di Scalabilità



La [scalabilità](https://it.wikipedia.org/wiki/Scalabilit%C3%A0) è l'incremento proporzionale di alcune prestazioni di un sistema quando viene impiegato più hardware. Il _throughput_ (n.d.t. capacità di processamento nell'unità di tempo) delle [transazioni](ch101-glossary.md#transazione) bitcoin è perfettamente non scalabile in quanto nessun quantitativo di hardware aggiuntivo può incrementarlo.

La [regola di consenso](ch101-glossary.md#regole-di-consenso) relativa limite alla dimensione del [blocco](ch101-glossary.md#blocco) stabilisce un compromesso arbitrario tra l'[utilità](ch101-glossary.md#utilità) e la sicurezza del sistema. Un aumento della dimensione del blocco incrementa marginalmente il _throughput_ delle [transazioni](ch101-glossary.md#transazione) e di conseguenza incrementa il costo delle risorse nella [validazione](ch101-glossary.md#validazione) delle stesse (i.e. elaborazione, storage, e banda). All'aumentare del costo di validazione, la sicurezza [economica](ch101-glossary.md#economia) è influenzata negativamente da un più elevato [rischio di centralizzazione](ch038-centralization-risk.md). Poiché il compromesso è arbitrario per natura, non può esistere una dimensione ideale (n.d.t. del blocco).

Per ogni dimensione del blocco adottata, il sistema non è scalabile poiché risulta necessario attendere la finalizzazione delle transazioni attraverso la [conferma](ch101-glossary.md#conferma). Poiché solo un numero finito di transazioni può essere selezionato per l'inclusione in un blocco, altre transazioni potrebbero risultare escluse. Questa esclusione è motivata a livello finanziario dal [costo opportunità](https://it.wikipedia.org/wiki/Costo_opportunit%C3%A0) di non utilizzare il capitale impiegato nel [mining](ch101-glossary.md#centro-di-mining-mine) e rappresenta la manifestazione della non scalabilità. Questa scarsità intrinseca necessita di un [mercato](ch101-glossary.md#mercato) competitivo delle conferme che viene finanziato in proporzione alla domanda di moneta.

L'effettiva capacità di supportare transazioni aggiuntive, e di conseguenza l'utilità, può essere incrementata dal [_layering_](ch101-glossary.md#layering). Questo rappresenta un compromesso di sicurezza di tipo _locale_ e _limitato nel tempo_ che si differenzia dal compromesso di sicurezza di tipo _sistemico_ e _persistente_ che caratterizza l'aumento della dimensione del blocco. Entrambi i compromessi abbassano ma non eliminano la [soglia di utilità](ch031-utility-threshold-property.md), cosa che implica la conservazione della [proprietà di stabilità](ch030-stability-property.md).

**Di conseguenza la stabilità e la non scalabilità esistono per ogni dimensione del blocco e per ogni livello di _layering_.**

---

Titolo originale: [Scalability Principle](https://github.com/libbitcoin/libbitcoin-system/wiki/Scalability-Principle)

[Indice](/README.md)

