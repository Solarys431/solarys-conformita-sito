![Solarys Conformità](marchio/intestazione.png)

[Live landing page](https://solarys431.github.io/solarys-conformita-sito/) ·
**Italiano** · [English](README.en.md)

**Prototipo funzionale di pre-audit documentale, requisito per requisito.**

Versione pubblica del prototipo: **v0.1.0**.

Legge i documenti di un cliente — visure, procedure, nomine, polizze, verbali,
valutazioni dei rischi — li confronta con requisiti documentali versionati e restituisce
una relazione di lavoro che distingue evidenze presenti, parziali, mancanti e da verificare.

Nella configurazione locale gira sul computer dello studio: documenti e prompt non vengono
inviati a servizi cloud e, dopo l'installazione dei modelli, l'analisi funziona anche offline.

---

## Non un parere: un riscontro

![Dal requisito al verdetto](media/riscontro-poster.jpg)

Gli esiti fondati su una prova positiva riportano la citazione riscontrata nel documento
originale. Se il passaggio non regge, il giudizio viene bloccato e inviato a revisione;
l'assenza di una prova resta dichiarata come tale.

Un esempio. Alla domanda *«questo poliambulatorio deve adempiere agli obblighi di
radioprotezione?»* un modello linguistico da 23 GB risponde **«Sì, è obbligatorio»**,
con l'elenco degli adempimenti e le sanzioni penali. È sbagliato, e non cita nulla.

La risposta giusta è **non dovuto**, e arriva con la prova:

> «la struttura NON dispone di apparecchiature radiogene né di diagnostica per immagini
> con radiazioni ionizzanti»

Non è questione di quanto è grande il modello: è il controllo che viene dopo.

---

## Un pre-audit sanitario da diciassette requisiti

![I requisiti che si chiudono uno a uno](media/requisiti-poster.jpg)

Si avvia l'analisi e si torna a lavorare. Al termine, la relazione di lavoro raccoglie:
rilievi, citazioni, scadenze calcolate. Fare lo stesso controllo a mano vuol dire
aprire decine di documenti e ricordare a memoria ogni obbligo di legge, da capo a ogni
aggiornamento del fascicolo.

---

## Il programma al lavoro

![I verdetti con le citazioni](media/prodotto-verdetto.jpg)

I giudizi compaiono mentre l'analisi procede, con norma, motivazione e, quando richiesta,
la prova testuale: un clic sulla citazione apre il documento da cui viene. In alto resta
il **quadro aziendale** — attività, organico, incarichi, apparecchiature — dove entrano
solo fatti con provenienza riscontrata; quelli contraddittori vengono isolati.

![I fascicoli dei clienti](media/prodotto-raccolte.jpg)

Ogni cliente è una raccolta a sé, indicizzata sulla macchina dello studio. La
configurazione locale non richiede chiavi API né consumo a token; restano i costi di
hardware, energia, manutenzione e revisione professionale.

---

## In breve

| | |
|---|---|
| **104 requisiti in sette insiemi** | sanità ambulatoriale, AML (presìdi dello studio e fascicolo cliente), studio legale, sicurezza sul lavoro, GDPR, modello 231 |
| **Tempo di analisi** | dipende da modello, hardware e quantità di documenti |
| **Configurazione locale** | documenti e prompt restano sul dispositivo durante l'analisi |
| **A chi serve** | commercialisti, avvocati, consulenti del lavoro, direttori sanitari, responsabili qualità e piccole imprese |

---

## Avvertenza

I fascicoli mostrati negli esempi — «Centro Medico Arcobaleno», «Studio Legale
Ferrario», «Studio Bianchi» — sono inventati, comprese le persone che vi compaiono.
Servono a mostrare il comportamento del programma e non descrivono strutture o
professionisti reali.

Il prototipo esegue un pre-audit documentale amministrativo. Non è consulenza legale,
non entra nel merito clinico, e non sostituisce il giudizio del professionista, che
resta l'unico responsabile della relazione che valida e firma.

---

© 2026 Daniele Cappello. Tutti i diritti riservati.

Il codice e i materiali sono consultabili pubblicamente, ma non sono distribuiti
con licenza open source. Consulta [`LICENSE`](LICENSE).

[Privacy](privacy.html) · [Accessibilità](accessibilita.html)
