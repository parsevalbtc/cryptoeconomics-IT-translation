# L'Argomento di Facciata della Prova di Memorizzazione



È stata formulata una [proposta](https://eprint.iacr.org/2017/893.pdf) secondo la quale una [prova di memorizzazione](ch101-glossary.md#prova-di-memorizzazione-proof-of-memory) (_proof-of-memory_ - PoM) possa sostituire una frazione del costo energetico della [_proof-of-work_](ch101-glossary.md#prova-di-lavoro-proof-of-work) (PoW) con un costo hardware, anche facendo affidamento sui dispositivi di memorizzazione esistenti. Come mostrato nella [Fallacia dello Spreco di Energia](ch053-energy-waste-fallacy.md), un livello di sicurezza costante richiede una spesa continuativa e costante. Di conseguenza questo sistema richiederebbe un equivalente livello di consumo di hardware per compensare ciascuna riduzione del costo energetico. **In altre parole il consumo totale di energia non può essere ridotto, può essere solo trasferito alla fabbricazione, al funzionamento e allo smaltimento di hardware.**

Nel dicembre 2017 il costo energetico annualizzato stimato dell'energia consumata nel mining Bitcoin è stato di 1'628'000'000 $ basato sull'approssimazione di 32,56 TWh consumati ad un costo di 0,05 $/kWh. Contemporaneamente, questo livello di costo è uguale al consumo di 32'560'000 terabyte di memoria ad un costo medio di 50 $ per dispositivo. L'utilizzo dei dispositivi esistenti inutilizzati riduce il costo unitario degli stessi e quindi innalza per confronto il quantitativo richiesto. 

Vale la pena analizzare il comportamento economico di un sistema teorico nel quale la PoM è determinata da un aggregato esistente di dispositivi di memorizzazione (a costo nullo) senza limite alla vita utile o costi operativi. Poiché in questo caso specifico il costo del [mining](ch101-glossary.md#centro-di-mining-mine) è pari a zero, le ricompense si trasferirebbero senza alcuna spesa in proporzione alla memoria posseduta (assumendo nessuna [pressione di raggruppamento](ch039-pooling-pressure-risk.md)). Ogni aumento delle commissioni medie va ad aumentare la ricompensa per la memoria. Il capitale [investito](ch101-glossary.md#dare-in-prestito---investire) è nullo e quindi il [tasso di ritorno](ch101-glossary.md#interesse) sarebbe perpetuamente infinito. Nonostante l'ipotesi di incentivo illimitato, l'assunzione di espansione nulla preclude ogni forma di competizione. Ma poiché la prova è esternalizzata, la competizione non può essere ristretta. In un sistema reale la fabbricazione di hardware si espande perpetuamente per un dato livello di [commissioni](ch101-glossary.md#commissione-di-transazione-fee), e questa espansione accelera all'aumentare del loro livello.

La _proof-of-memory_ è uguale alla _proof-of-work_ in termini del consumo di risorse e non vi è ragione di assumere alcuna riduzione della componente energetica di tale costo. L'hardware si comporta come una prova di immagazzinamento di energia (una batteria) che rappresenta l'energia che è stata spesa in maniera dimostrabile per la sua fabbricazione. Quello che è stato confutato qui è un argomento di facciata analogo a quello delle automobili elettriche con batteria "a zero emissioni".

---

Titolo originale: [Proof of Memory Façade](https://github.com/libbitcoin/libbitcoin-system/wiki/Proof-of-Memory-Façade)

[Indice](/README.md)

