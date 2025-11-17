Strumento 20 - Schema Editor
============================

20.1 - Anagrafica
-----------------

**Ente:** ISTAT

**Ufficio proponente:** DIRM - Dipartimento per lo sviluppo di metodi e tecnologie
per la produzione e diffusione dell'informazione statistica  

**Destinatari:** Tutte le pubbliche amministrazioni  

**Capitolo del PT 2024-2026:** Capitolo 5 - Dati e intelligenza artificiale

**Tematica:** Open data e data governance


20.2 - Scenario
---------------

Nell'ambito della strategia di trasformazione digitale della Pubblica 
Amministrazione, l'interoperabilità semantica svolge un ruolo rilevante. 
Infatti, Progetti come il **Catalogo Nazionale per l'interoperabilità semantica 
dei dati (NDC) (a)** e la **Piattaforma Digitale Nazionale Dati (PDND) (b)**, 
entrambi finanziati dal PNRR, Sub-investimento 1.3.1, sono fondamentali per 
abilitare uno scambio di informazioni efficiente e automatico tra gli enti 
pubblici. Questo approccio risponde alle direttive del *European Interoperability 
Framework*, all'*Interoperable Europe Act* e alle normative nazionali, come il CAD 
(Codice per l'Amministrazione Digitale) e Linee guida sull'interoperabilità 
tecnica delle Pubbliche Amministrazioni. (c).

Per implementare l'interoperabilità tecnica e semantica dei dati è necessario 
definire il modello dello scambio dei dati e delle relative informazioni, in 
modo che i dati e i metadati “viaggino” insieme in un formato standard 
interpretabile da una macchina.

La progettazione di modelli per lo scambio dati risulta molto più efficace e 
comprensibile se si basa su **schemi dati**, ovvero descrizioni condivise di un 
insieme di dati, che fanno riferimento a ontologie e vocabolari controllati. 
Ontologie e vocabolari controllati sono a loro volta descrizione condivise delle 
informazioni di un particolare settore.

La documentazione delle API (*Application Programmer's Interface*) che compongono 
un e-service è normalmente pubblicata nello standard OpenAPI. Gli schemi dati 
possono essere realizzati nel formato JSON-LD. Il Dipartimento per la 
Trasformazione Digitale e ISTAT hanno proposto un'estensione del formato OpenAPI, 
che permette di inserire le descrizioni degli schemi dati direttamente all'interno 
della documentazione delle API. La coesistenza di entrambe le informazioni nello 
stesso documento rende tutto più coerente ed efficiente e mostra immediatamente 
la correlazione fra la specifica delle interfacce e gli schemi usati per i dati 
scambiati.

La progettazione degli schemi dati e l'inserimento di queste informazioni 
all'interno della specifica OpenAPI richiedono la consultazione di molte 
informazioni e la gestione dei file di specifica, per cui è utile avere a 
disposizione strumenti che rendano più semplice questo lavoro.

Per superare questa sfida e supportare le pubbliche amministrazioni, viene 
messo a disposizione lo **schema editor**, uno strumento progettato per guidare 
l'erogatore di e-service su PDND, anche meno esperto, nella creazione di schemi 
dati conformi agli standard nazionali e internazionali. Lo scopo è garantire che 
i dati esposti tramite e-service siano coerenti e semanticamente interoperabili, 
pronti per essere utilizzati all'interno della PDND e referenziati nel catalogo 
www.schema.gov.it.

20.3 - Presentazione
--------------------
Lo **schema editor** (d) è destinato a tutte le pubbliche amministrazioni e 
alle organizzazioni che intendono esporre i propri servizi tramite e-service, 
garantendo l'aderenza ai principi di interoperabilità semantica e a quanti 
vogliono pubblicare “Schemi Dati” sul catalogo www.schema.gov.it. Lo strumento 
è attualmente in versione **beta** e in continua evoluzione.

Quando un ente ha la necessità di sviluppare un nuovo e-service, lo strumento 
offre un ambiente guidato per progettare il relativo schema dati. L'utente opera 
in un ambiente interattivo che offre:

- **Area di editing:** L'editor per scrivere la specifica dell'API in formato 
  YAML o JSON, seguendo la *OpenAPI Specification* (OAS), lo standard più diffuso 
  per la descrizione delle API REST (e);

- **Validazione in tempo reale:** Mentre si scrive, lo strumento controlla 
  costantemente sia la correttezza della sintassi (secondo lo standard OAS) 
  sia la conformità alle linee guida nazionali;

- **Anteprima interattiva della documentazione:** A fianco del codice, viene 
  mostrata un'anteprima navigabile dell'API, che elenca endpoint, parametri e 
  risposte. Questa interfaccia può essere usata per eseguire la simulazione di 
  chiamate di prova.

L'utilizzo dello schema editor assicura che il modello dati sottostante a un'API 
sia robusto, riutilizzabile e compreso in modo univoco da tutti gli attori 
dell'ecosistema, in linea con il principio europeo *“once only”*. In questo modo, 
si semplifica l'integrazione tra sistemi, si riducono i costi e si accelera la 
creazione di servizi digitali integrati per cittadini e imprese. Lo sviluppo di 
schemi dati che si applicano a diverse API consente il riuso del codice di 
annotazione semantica di un servizio automatico. In particolare, degli *e-service* 
pubblicati sulla PDND, garantendo che i dati siano scambiati già corredati di 
metadati che consentono anche di garantire la consistenza definitoria e sintattica 
delle ontologie.

20.4 - Quadro di sintesi - elementi chiave
------------------------------------------

Per realizzare lo *schema editor*, il processo di sviluppo ha seguito diverse 
fasi strategiche:

1. **Analisi dei requisiti**: sono state analizzate le Linee Guida 
   sull'interoperabilità tecnica delle PPAA e le principali difficoltà 
   incontrate dalle PA nella progettazione degli schemi dati, al fine di 
   definire le funzionalità essenziali dello strumento;

2. **Progettazione dell'esperienza utente (UX)**: sono state condotte sessioni di
   progettazione per creare un'interfaccia intuitiva e un flusso di lavoro guidato,
   accessibile anche a utenti senza competenze tecniche avanzate in modellazione
   semantica;

3. **Sviluppo e Test**: lo strumento è stato sviluppato e successivamente testato in
   un ambiente dedicato, coinvolgendo un gruppo pilota di amministrazioni per
   raccogliere feedback e perfezionarne le funzionalità prima del rilascio.

20.5 - Risorse utili
--------------------

-  `Catalogo Nazionale della Semantica dei Dati (NDC) (a) <https://schema.gov.it/>`__

-  `Piattaforma Digitale Nazionale Dati (PDND) (b) <https://www.interop.pagopa.it/>`__

-  `Linee guida sull'interoperabilità tecnica delle Pubbliche Amministrazioni (AgID)
   (c) <https://www.agid.gov.it/sites/agid/files/2024-05/linee_guida_interoperabilit_tecnica_pa.pdf>`__

-  `Schema editor (d) <https://schema.gov.it/schema-editor>`__

-  `Documentazione per la progettazione di API REST della PA (e) <https://developers.italia.it/it/interoperabilita>`__

