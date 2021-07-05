# Principio dei Dati Pubblici



Dal [Principio di Condivisione dei Rischi](ch016-risk-sharing-principle.md) consegue che la sicurezza del sistema dipende dalle attività di [mining](ch101-glossary.md#centro-di-mining-mine) e di [scambio](ch101-glossary.md#scambio) svolte sotto copertura. Una [moneta](ch101-glossary.md#moneta) esiste sotto forma di un [mercato](ch101-glossary.md#mercato) [mutuamente vantaggioso](ch042-balance-of-power-fallacy.md) tra i [miner](ch101-glossary.md#miner) e i [commercianti](ch101-glossary.md#commerciante) basato sulla [conferma](ch101-glossary.md#conferma) di [transazioni](ch101-glossary.md#transazione) all'interno dei blocchi in cambio di [_fee_](ch101-glossary.md#commissione-di-transazione-fee).

Le attività che avvengono necessariamente sotto copertura sono suddivise per ruolo:

**Miner**

1. ottenere i blocchi [sui quali aggiungere (nuovi blocchi)]
2. ottenere transazioni non confermate [da cui guadagnare commissioni]
3. creare e distribuire blocchi [affinché altri possano aggiungere sopra (nuovi blocchi)] 
4. ricevere pagamenti in cambio di conferme [per finanziare le proprie operazioni]

**Commercianti**

1. ottenere blocchi [per validare i pagamenti dei clienti]
2. ottenere transazioni non confermate (opzionale) [per anticipare pagamenti e _fee_]
3. creare e distribuire transazioni [per ottenere il pagamento dei clienti]
4. effettuare pagamenti in cambio di conferme [per remunerare le conferme]

Se i blocchi non possono essere ottenuti anonimamente il sistema non è sicuro. L'impossibilità di ottenere i blocchi del [ramo più forte](ch101-glossary.md#ramo-forte-strong-branch) disponibile ad altre [persone](ch101-glossary.md#persona) rappresenta una [partizione](ch101-glossary.md#partizione) della rete e costituisce una falla localizzata nella sicurezza. Tuttavia, né l'anonimità né il suo opposto, [l'identità](ch101-glossary.md#identità), possono assicurare che un individuo osservi il [ramo](ch101-glossary.md#ramo-branch) più forte della catena. In altre parole, ogni sforzo teso a mitigare il partizionamento con l'introduzione dell'identità rappresenta una [falsa dicotomia](https://it.wikipedia.org/wiki/Falsa_dicotomia) che sacrifica la sicurezza di sistema in cambio della erronea pretesa di garantire la sicurezza in forma localizzata.

Non è essenziale che tutti i miner o i commercianti vedano tutte le transazioni in ogni momento. Tuttavia, un'ampia visibilità è preferibile in quanto produce la più robusta competizione tra le _fee_ e la massima informazione. In altre parole un mercato nel quale ogni partecipante vede tutte le transazioni in ogni momento è un [mercato in concorrenza perfetta](https://it.wikipedia.org/wiki/Concorrenza_perfetta). Richiedere alla rete transazioni specifiche, rispetto a richiederle tutte (o richiedere informazioni riassuntive di tutte) rappresenta una possibile forma di tracciamento e, come tale, deve essere evitata anche nell'interesse della sicurezza.

La creazione di blocchi e di transazioni non espone in maniera intrinseca l'identità, tuttavia la distribuzione pubblica degli stessi è la fonte principale del [tracciamento](ch101-glossary.md#tracciamento-taint). Nella misura in cui i miner rivelano apertamente la loro identità, essi stanno facendo affidamento sull'ipotesi di [un ambiente a basso livello di minaccia](ch033-threat-level-paradox.md) e non contribuiscono alla sicurezza del sistema. Evitare il tracciamento mentre si inoltrano blocchi e transazioni richiede l'uso di una [connessione anonima](https://en.wikipedia.org/wiki/Anonymizer) ad un [server](ch101-glossary.md#client-server) della comunità (n.d.t. un nodo bitcoin). Questo garantisce che la [rete del protocollo peer to peer](ch101-glossary.md#peer-to-peer) non abbia mai modo di accedere ad informazioni che portino ad identificazione.

La [proof-of-work](ch101-glossary.md#prova) garantisce l'anonimità dei miner. Infatti, non vi è firma associata al mining e si assume che l'energia sia disponibile in maniera diffusa. Analogamente, l'abilità di pagare anonimamente per ottenere la conferma è la ragione per la quale vengono incluse le _fee_ di transazione. E' [sufficiente](ch081-side-fee-fallacy.md) pagare un miner direttamente (off-[chain](ch101-glossary.md#catena)) per avere conferma della transazione, tuttavia questo espone reciprocamente sia il commerciante che il miner e rende più difficile stimare le _fee_ in maniera anonima.

Bitcoin è un sistema innovativo perché tutte le transazioni finanziarie possono essere [validate](ch101-glossary.md#validazione) a partire da dati pubblici e senza l'uso dell'identità. I sistemi finanziari centralizzati si basano sulla fiducia nelle connessioni con altre controparti (attraverso l'identificazione in forma crittografata) o nella fiducia nelle firme (verificabili in maniera crittografica) che accompagnano i dati trasmessi. Questa è l'essenza dei sistemi basati sulla fiducia; alcune autorità hanno dei segreti che gli altri usano per verificare la loro autenticità. **La ragione alla base della validazione è quella di eliminare l'uso dell'identità e di conseguenza quello dell'autorità.**

---

Titolo originale: [Public Data Principle](https://github.com/libbitcoin/libbitcoin-system/wiki/Public-Data-Principle)

[Indice](/README.md)
