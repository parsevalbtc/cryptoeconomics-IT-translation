# Fallacia della Prova di Proprietà



Esiste una teoria secondo la quale la [titolarità](ch101-glossary.md#proprietario) di una proprietà può essere protetta attraverso l'adozione di un registro immutabile dei [titoli di proprietà](ch101-glossary.md#ricorrente-claimant), efficace sia contro la perdita del titolo sia contro il [Rischio di Custodia](ch009-custodial-risk-principle.md).

Poiché il titolo di proprietà non è di per sé la proprietà da esso stesso rappresentata, il controllo della proprietà resta affidato al [custode](ch101-glossary.md#custode) verso il quale ha valenza il titolo di proprietà.  Un custode ha la possibilità di restituire o trattenere la proprietà e quindi egli si configura come una [terza parte fidata](https://en.wikipedia.org/wiki/Trusted_third_party). L'annullamento di un titolo di proprietà da parte del custode è sempre mitigato dalla firma del custode, sia in forma crittografica o di diversa natura, dove il compito di far valere il titolo viene lasciato al suo possessore. 

La teoria afferma che un registro immutabile dei titoli fornisce protezione contro la perdita del titolo da parte del suo possessore, in quanto nessun altro individuo avrebbe un interesse in tale perdita. Tuttavia, per riscattare il titolo, il suo possessore deve fornire una prova di proprietà al custode. Questo richiede che il possessore non perda il segreto che fornisce la prova della sua proprietà. Come tale la protezione del titolo contro la perdita non è affatto mitigata, cambia solamente forma. La teoria è quindi invalida sulla base della prevenzione dalla perdita.

Conservare un riferimento solido al titolo può ridurre la dimensione, e quindi il costo, della sua inalterabile conservazione. Il titolo può essere costruito nella forma di un contratto in forma leggibile dalle [persone](ch101-glossary.md#persona) o da una [macchina](ch101-glossary.md#macchina), e referenziato attraverso un [hash non invertibile](https://it.wikipedia.org/wiki/Funzione_crittografica_di_hash). In ogni caso, è richiesta la [validazione](ch101-glossary.md#validazione) e l'esecuzione del contratto al fine di trasferire la proprietà dal custode. Di conseguenza un contratto referenziato sopperisce al rischio di perdita con dati addizionali, ovvero con il contratto stesso.

Come mostrato nel [Principio della Condivisione del Rischio](ch016-risk-sharing-principle.md), alla base della sicurezza ci sono sempre le persone. Le persone possono agire collettivamente per proteggere l'immutabilità di una moneta e di conseguenza possono anche proteggere i dati di titolarità associati al controllo della moneta. Tuttavia, il custode è una terza parte fidata. Titoli di tipo immutabile non mitigano in nessun modo attacchi diretti compiuti contro il custode, o dal custode stesso. Quando il custode è lo [stato](ch101-glossary.md#stato) o un'entità assoggettata al suo controllo, il titolo non offre [alcuna sicurezza](https://it.wikipedia.org/wiki/Ordine_esecutivo_6102) contro la sostituzione dell'autorità dello stato a qualsiasi prova di titolarità. La teoria è quindi anche invalida sotto il profilo del fallimento del custode.

Bitcoin come moneta funziona senza custodia (è _non-custodial_). Le sue [unità](ch101-glossary.md#unità) non rappresentano un asset custodito da una terza parte fidata. La moneta è scambiata direttamente tra cliente e [commerciante](ch101-glossary.md#commerciante). In questo senso _tutti i commercianti_ sono i custodi del [valore](ch101-glossary.md#valore) di Bitcoin. **La fallacia della blockchain (n.d.t. che si identifica con la fallacia della prova di proprietà ndt), nasce da una concezione errata del modello di sicurezza di Bitcoin, che attribuisce la sua protezione alla tecnologia e non alla sua distribuzione tra i commercianti**. Il termine "tecnologia blockchain" rafforza questo errore poiché implica che sia principalmente la struttura dati di Bitcoin a renderlo sicuro.

---------
Titolo originale: [Proof of Ownership Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Proof-of-Ownership-Fallacy)

[Indice](/README.md)



