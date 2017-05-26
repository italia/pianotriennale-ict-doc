Modello di interoperabilità
===========================

Il Modello di interoperabilità rappresenta un asse portante necessario
al funzionamento dell’intero Sistema informativo della Pubblica
amministrazione.

Questo Modello rende possibile la collaborazione tra Pubbliche
amministrazioni e tra queste e soggetti terzi, per mezzo di soluzioni
tecnologiche che assicurano l’interazione e lo scambio di informazioni
senza vincoli sulle implementazioni, evitando integrazioni ad hoc.

Il Modello di interoperabilità:

-  abilita lo sviluppo di nuove applicazioni per gli utenti della PA, in
   coerenza con le attività descritte nel capitolo 7 “Strumenti per la
   generazione e diffusione di servizi digitali” e con gli obiettivi del
   Piano;

-  garantisce il dialogo all’interno dei singoli ecosistemi e tra un
   ecosistema e l’altro;

-  regola l'utilizzo delle componenti delle Infrastrutture immateriali,
   disciplinandone le modalità di condivisione e pubblicazione;

-  disciplina le modalità con le quali vengono inviati i flussi di dati
   verso il Data & Analytics Framework;

-  assicura, nel rispetto del diritto alla privacy, l’accesso ai dati
   della Pubblica amministrazione anche a soggetti terzi;

-  è progettato in coerenza con i principi ancora validi declinati nello
   `European Interoperability
   Framework <https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa_annex_ii_eif_en.pdf>`__
   (EIF) versione 2.0 [66]_, pubblicato nel 2010 nell’ambito del
   programma `Interoperability solutions for public administrations,
   businesses and
   citizens <https://ec.europa.eu/isa2/isa2_en>`__\  [67]_ (ISA, dal
   2016 ISA²).

Scenario Attuale
----------------

Nell’ottobre 2005, il CNIPA (oggi AgID) ha pubblicato un insieme di
documenti che costituiscono il riferimento tecnico per
l’interoperabilità fra le Pubbliche amministrazioni. Tali documenti
delineano il quadro tecnico-implementativo del Sistema pubblico di
cooperazione (SPC Coop). Presso AgID è in fase di consolidamento la
definizione del nuovo Modello di interoperabilità che supera il modello
precedente e verrà definito con apposite linee guida.

Il nuovo Modello, secondo quanto previsto dalle recenti modifiche del
CAD con l'abrogazione dell'articolo 58, permette di superare la
necessità di convenzioni per lo scambio di informazioni punto a punto.

Obiettivi strategici
--------------------

-  Armonizzare le scelte architetturali della Pubblica amministrazione,
   specificando le condizioni necessarie all’adesione al Sistema
   informativo della PA.

-  Creare le condizioni tecnologiche che favoriscano lo sviluppo, da
   parte di amministrazioni e imprese, di soluzioni applicative
   innovative orientate al cittadino, alle imprese e alla Pubblica
   amministrazione, e che abilitino l’utilizzo dei servizi descritti nel
   capitolo 4 “Infrastrutture Immateriali”.

-  Promuovere l’adozione dell’approccio API first al fine di favorire la
   separazione dei livelli di back end e front end, con logiche aperte e
   standard pubblici che garantiscano ad altri attori, pubblici e
   privati, accessibilità e massima interoperabilità di dati e servizi.

-  Privilegiare standard tecnologici che soddisfino l’esigenza di
   assicurare le interazioni tra le Pubbliche amministrazioni e di
   queste con i cittadini e le imprese.

-  Abilitare il flusso di dati utile al popolamento del Data & Analytics
   Framework.

-  Semplificare le procedure di scambio di servizi tra le Pubbliche
   amministrazioni e, ove possibile, tra Pubblica amministrazione e
   privati, attraverso la pubblicazione nelle linee guida sulle regole
   di partecipazione.

-  Assicurare la conformità alle linee guida e promuovere la qualità dei
   servizi esposti dalla PA.

Linee di azione
---------------

Il Modello di interoperabilità definisce le linee guida che tutte le
Pubbliche amministrazioni dovranno adottare al fine di garantire
l’interoperabilità dei propri sistemi con quelli di altri soggetti e
l’implementazione complessiva del Sistema informativo della PA.

Gli standard tecnologici rispecchieranno le *best practice* nell’ambito
dell’interoperabilità dei sistemi informativi e/o saranno aderenti a
standard consolidati, anche in ambito EU.

Tutte le amministrazioni devono aderire agli standard tecnologici e ai
profili di interoperabilità del nuovo Modello di interoperabilità che
consente di definire ed esporre *Application Programming Interface*
(API) conformi.

Le API dovranno rifarsi alle migliori pratiche di gestione (API
management), prevedendo in particolare:

-  tracciabilità delle diverse versioni delle API, allo scopo di
   consentire evoluzioni non distruttive (*versioning*);

-  documentazione coordinata con la versione delle API
   (*documentation*);

-  gestione degli utilizzatori, in particolare autenticazione e
   autorizzazione (*user management, authentication, authorization*);

-  limitazioni di utilizzo collegate alle caratteristiche delle API
   stesse e della classe di utilizzatori (*throttling*);

-  tracciabilità delle richieste ricevute e del loro esito (*logging e
   accounting*), anche al fine della non ripudiabilità della
   comunicazione;

-  ambiente di test;

-  pacchetti software per l’interfacciamento per i servizi strategici di
   terze parti (SDK);

-  un adeguato livello di servizio in base alla tipologia del servizio
   fornito (SLA);

-  configurazione scalabile delle risorse;

-  pubblicazione di metriche di utilizzo (*analytics*).

In quest’ottica non esiste un elemento unico centralizzato
(*middleware*) che media l’accesso ai servizi della PA ed è previsto
invece che AgID, direttamente o indirettamente:

-  fornisca un catalogo distribuito delle API e dei servizi disponibili
   con una interfaccia di accesso unica;

-  verifichi il rispetto delle regole del Modello di interoperabilità,
   quale condizione di accesso al catalogo;

-  controlli con continuità il rispetto dei requisiti per l’iscrizione
   al catalogo;

-  coadiuvi la risoluzione di problematiche con appositi strumenti di
   cooperazione (ad es.help desk, forum, mailing list e newsletter);

-  stabilisca, pubblichi e controlli le metriche di utilizzo;

-  metta a disposizione librerie e SDK per fornire molte delle
   funzionalità definite dalle linee guida.

Coerentemente con l'abrogazione dell'articolo 58 del CAD non serviranno
più convenzioni tra amministrazioni; AgID stabilirà nelle linee guida le
modalità di adesione alle API.

Le Pubbliche amministrazioni saranno responsabili della definizione dei
termini di utilizzo delle API da loro esposte.

In seguito verranno definite le regole per l'adesione dei soggetti
privati.

Al fine di favorire e coordinare tutte le attività, AgID:

-  offrirà supporto alle attività descritte nel capitolo 6 “Ecosistemi”
   e, più in generale, alle amministrazioni impegnate nelle attività di
   adeguamento dei propri sistemi al nuovo Modello di interoperabilità;

-  assicurerà che il Modello di interoperabilità sia costantemente
   aggiornato dal punto di vista tecnologico.

+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Oggetto       | Linee guida del nuovo Modello di interoperabilità                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tempi         | Entro dicembre 2017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Attori        | AgID                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione   | Emanazione delle linee guida utili alle Pubbliche amministrazioni e agli altri attori del Sistema informativo della PA per aderire al Modello di interoperabilità. Più precisamente verranno fornite le indicazioni che dovranno essere adottate (in termini di standard tecnologici, di profili di interoperabilità e di protocolli di comunicazione) per la realizzazione delle API necessarie all’adeguamento delle componenti descritte nel capitolo 4 “Infrastrutture immateriali” e nel capitolo 6 “Ecosistemi”. Verranno altresì fornite le indicazioni per la realizzazione delle nuove applicazioni per gli utenti finali, descritte nel capitolo 7 “Strumenti per la generazione e diffusione di servizi digitali” e per il popolamento del *Data & Analytics Framework.* |
|               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|               | La pubblicazione delle linee guide sarà preceduta dall’emissione di un documento riportante la roadmap di evoluzione dal vecchio al nuovo modello ed un piano di phase-out per gli elementi infrastrutturali, previsti dal vecchio modello, in via di dismissione.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Risultato     | Linee guida per transitare al nuovo Modello di interoperabilità *(data di rilascio: maggio 2017)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|               | Linee guida del nuovo Modello di interoperabilità *(data di rilascio versione 1.0: dicembre 2017)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Oggetto       | Adozione del Modello da parte delle PA                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tempi         | Da maggio 2017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Attori        | AgID, PA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione   | Per le piattaforme esistenti e per le attività progettuali già in corso le PA adottano le linee guida di transizione, mentre per le nuove realizzazioni si adeguano al nuovo Modello.                                                                                                                                                                                                                                                                                                                      |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Risultato     | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Oggetto       | Catalogo delle API                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tempi         | Da giugno 2017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Attori        | AgID                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione   | AgID realizzerà un apposito Catalogo delle API, che consentirà la condivisione delle API realizzate dalla PA. Attraverso le informazioni registrate nel Catalogo si realizza un punto di esposizione nel quale saranno censite e documentate le API condivise dagli utenti e utili agli sviluppatori e agli altri soggetti coinvolti negli Ecosistemi. Nondimeno, nel rispetto del diritto alla privacy in merito ai dati trattati, le API potranno essere utilizzate anche da soggetti esterni alla PA.   |
|               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|               | AgID definirà un apposito set di regole di utilizzo e un modello di governance per la gestione.                                                                                                                                                                                                                                                                                                                                                                                                            |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Risultato     | Prima release del Catalogo (*data di rilascio: dicembre 2017*)                                                                                                                                                                                                                                                                                                                                                                                                                                             |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Oggetto       | Popolamento catalogo API                                                                                                                                                                                                  |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tempi         | Da gennaio 2018                                                                                                                                                                                                           |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Attori        | PA                                                                                                                                                                                                                        |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione   | Le PA, nell’attuazione delle regole del Modello di interoperabilità, daranno seguito all’implementazione di API e al successivo popolamento del Catalogo, al fine di agevolarne l’utilizzo da parte degli sviluppatori.   |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Risultato     | ---                                                                                                                                                                                                                       |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. rubric:: Note

.. [66]
   `https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa\_annex\_ii\_eif\_en.pdf <https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa_annex_ii_eif_en.pdf>`__

.. [67]
   `https://ec.europa.eu/isa2/isa2\_en <https://ec.europa.eu/isa2/isa2_en>`__
