# Principio dei Dati Pubblici



Dal [Principio di Condivisione dei Rischi]() segue che la sicurezza del sistema dipende dalle attività sotto copertura di [mining]() e [scambio](). Un [moneta]() esiste sotto forma di [mercato]() [mutaumente vantaggioso]() tra i [miner]() e i [commercianti]() per la [conferma]() di [transazioni]() all'interno dei blocchi in cambio di [commissioni]() (fee).

Le attività che avvengono necessariamente sotto copertura sono suddivise per ruolo:

**Miner**

1. ottenere i blocchi [sui quali costruire (nuovi blocchi)]
2. ottenere transazioni non confermate [da cui guadagnare commissioni]
3. creare e distribuire blocchi [affinché altri possano costruirvi sopra (nuovi blocchi)] 
4. ricevere il pagamento in cambio delle conferme [per finanziare le proprie operazioni]

**Commercianti**

1. ottenere blocchi [per validare i pagamenti dei clienti]
2. ottenere transazioni non confermate (opzionale) [per anticipare pagamenti e commissioni]
3. creare e distribuire transazioni [per ottenere il pagamento dei clienti]
4. effettuare pagamenti in cambio di conferme [per remunerare le conferme]

Si i blocchi non possono essere ottenuti anonimamente in sistema non è sicuro. L'impossibilità di ottenere i [più forti]() blocchi disponibili rappresenta per altre [persone]() una [partizione]() della rete, che costituisce una falla localizzata nella sicurezza. Tuttavia né l'anonimità né il suo opposto, l'identità, possono assicurare che un individuo osservi il [ramo]() più forte della catena. In altre parole, ogni sforzo teso a mitigare il partizionamento con l'introduzione dell'identità è una [falsa dicotomia]() che sacrifica la sicurezza di sistema in cambio della falsa pretesa di assicurare la sicurezza in forma localizzata.

Non è essenziale che tutti i miner o i commercianti vedano tutte le transazioni ad ogni dato istante di tempo. Tuttavia una ampia visibilità è preferibile in quanto produce la più robusta competizione tra le commissioni e la massima informazione. In altre parole un mercato nel quale ogni partecipante vede tutte le transazioni in ogni instante è un [mercato perfetto](). Richiedere alla rete transazioni specifiche, rispetto a tutte (o a informazioni riassuntive di tutte), è una fonte di possibilità di tracciamento e deve essere evitata allo stesso modo nell'interesse della sicurezza.

La creazione di blocchi e transazioni non espone in maniera intrinseca l'identità, tuttavia la distribuzione pubblica degli stessi e la fonte principale del [tracciamento](). Nella misura in cui i miner si identificano in maniera aperta, essi stanno facendo affidamento sull'ipotesi di [un ambiente a basso livello di minaccia](), e non contribuiscono alla sicurezza del sistema. Evitare il tracciamento mentre si inoltrano blocchi e transazioni richiede l'uso di una [connessione anonima]() ad un server comune. Questo garantisce che la rete di distribuzione non abbia mai modo di accedere ad informazioni che portino ad identificazione.

La [proof-of-work]() garantisce l'anonimità dei miners. Non vi è firma associata al mining e viene assunto che l'energia sia disponibile in maniera diffusa. Analogamente, l'abilità di pagare anonimamente per avere la conferma è la ragione per la quale vengono incluse le commissioni di transazione. E' [sufficiente]() pagare un miner direttamente (off chain) per avere conferma della transazione, tuttavia questo espone il commerciante ed il miner reciprocamente, e rende maggiormente difficile stimare le commissioni in maniera anonima.

Bitcoin è innovativo in quanto tutte le transazioni finanziarie possono essere [validate]() da dati pubblici e senza identità. I sistemi finanziari centralizzati si basano sulla fiducia nelle connessioni con altre controparti (attraverso l'identificazione in forma crittografata) o nella fiducia nelle firme (verificabili in maniera crittografica) che accompagnano i dati trasmessi. Questa è l'essenza dei sistemi basati sulla fiducia; alcune autorità hanno dei segreti che gli altri usano per verificare la loro autenticità. **La ragione alla base della validazione è quella di eliminare l'uso dell'identità e di conseguenza dell'autorità.**





