Modello di interoperabilità
===========================

Il Modello di interoperabilità (di seguito Modello) rappresenta un asse portante
necessario all’attuazione del Piano Triennale, rendendo possibile la
collaborazione tra pubbliche amministrazioni e tra queste e soggetti terzi
(cittadini e imprese).

Il Modello ha come obiettivo la creazione di un “Sistema informativo della PA”
che assicuri l’interazione e lo scambio di informazioni senza vincoli sulle
implementazioni, evitando integrazioni ad hoc.

Il Modello è progettato in coerenza con i principi declinati nello `European
Interoperability Framework
<https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa_annex_ii_eif_en.pdf>`__
(EIF) versione 2.0, pubblicato nel 2017 nell’ambito del programma
`Interoperability solutions for public administrations, businesses and citizens
<https://ec.europa.eu/isa2/isa2_en>`__ (ISA, dal 2016 ISA²).

Il Modello favorisce l’attuazione del principio *once only* secondo il quale le
PA devono evitare di chiedere ai cittadini e imprese informazioni già fornite.

Nello specifico, il Modello definisce gli standard e le loro modalità di
applicazione, che le PA utilizzano per assicurare la comunicazione tra i propri
sistemi informativi e tra questi e soggetti terzi.

Il Modello di interoperabilità:

- individua gli standard per favorire le scelte tecnologiche su cui costruire
  una *API economy* della PA;

- abilita lo sviluppo di nuove applicazioni per gli utenti della PA, in
  coerenza con le attività descritte nel capitolo 9 “Strumenti per la
  generazione e diffusione di servizi digitali” e con gli obiettivi del Piano;

- garantisce il dialogo all’interno dei singoli Ecosistemi (capitolo 7) e tra
  un ecosistema e l’altro;

- regola l’utilizzo dei componenti delle Piattaforme (capitolo 6),
  disciplinando le modalità di condivisione e pubblicazione;

- assicura, nel rispetto del diritto alla *privacy*, l’accesso ai dati della
  Pubblica Amministrazione (capitolo 5) anche a soggetti terzi.

Scenario
--------

Il nuovo Modello sostituisce quello precedente (SPCoop) emanato nel 2005.

Tutte le pubbliche amministrazioni devono adottare le Linee guida sul Modello di
interoperabilità per far interoperare i propri sistemi con quelli di altri
soggetti.

Per le piattaforme esistenti e le attività progettuali in corso, nell’agosto
2017 l’AGID ha definito, nelle `Linee guida per transitare al nuovo Modello di
Interoperabilità (Determina 219/2017),
<https://www.agid.gov.it/sites/default/files/repository_files/upload_avvisi/linee_guida_passaggio_nuovo_modello_interoperabilita.pdf>`__
le azioni che le pubbliche amministrazioni devono realizzare al fine di dare
seguito al processo di transizione al nuovo Modello.

Per agevolare questa migrazione, AGID:

- raccoglie e pubblica i piani di dismissione ricevuti dalle PA che mettono a
  disposizione i propri servizi (PA erogatrici);

- favorisce la condivisione delle informazioni necessarie tra le PA erogatrici
  e i soggetti che utilizzano i servizi esposti.

AGID ha rilasciato i primi due capitoli del nuovo Modello, definendo il quadro
di riferimento tecnico per l’implementazione dei servizi web nella PA, con
particolare riferimento agli standard SOAP e REST, quali buone pratiche
nell’ambito dell’interoperabilità dei sistemi informativi.

Tutte le amministrazioni adottano gli standard tecnologici e le indicazioni del
nuovo Modello per definire le “Interfacce di servizio”, tra cui API che si
declinano nell’adozione degli standard REST e SOAP che espongono un servizio
digitale.

Da un punto di vista tecnico, per semplificare gli aggiornamenti e limitare gli
impatti degli adeguamenti normativi, la progettazione e implementazione di ogni
Interfaccia di servizio deve:

- assicurare un’alta coesione delle funzionalità;

- avere un ciclo di vita il più possibile autonomo;

- garantire il basso accoppiamento.

La progettazione delle Interfacce di servizio deve tener presente le interazioni
tra i vari servizi, a tutela più generale del “Sistema informativo della PA” che
ne risulta e dei suoi utenti.

La gestione delle Interfacce di Servizio, tra l’altro, assicura:

- un adeguato livello di servizio in base alla tipologia del servizio fornito
  (*Service Level Agreement -* SLA);

- la tracciabilità delle diverse versioni (*versioning*) per consentire
  evoluzioni non distruttive;

- la presenza di documentazione coordinata con la versione delle Interfacce di
  servizio (*documentation*);

- l’autenticazione/autorizzazione per l’accesso ai servizi (*authentication e
  authorization*);

- la gestione dello stato di disponibilità dei servizi (*availability
  management*);

- la tracciabilità delle richieste e risposte ricevute e del loro esito
  (*logging e accounting*);

- la pubblicazione di metriche di utilizzo (*analytics*).

Essa prevede, in maniera commisurata alle esigenze del servizio:

- la tracciabilità delle informazioni necessarie al non ripudio della
  comunicazione;

- la disponibilità dell’ambiente di test;

- la configurazione elastica delle risorse;

- i pacchetti software per l’interfacciamento per i servizi strategici di terze
  parti (SDK).

Nel Modello non è previsto un elemento unico centralizzato (*middleware*) che
media l’accesso ai servizi della PA, ma un “Catalogo delle Interfacce di
servizio” (di seguito Catalogo) che pubblica le Interfacce di Servizio e i
relativi livelli di servizio dichiarati.

La gestione del Catalogo implementa il modello di *governance* attraverso una
piattaforma centralizzata e *multi-tenant*, che potrà determinare la
specializzazione del Catalogo, prevedendo contenuti con un livello di
aggregazione tematica e/o territoriale.

Il Catalogo, cioè, segue due direttrici:

- una tematica, legata agli Ecosistemi (ad esempio, la Giustizia);

- una territoriale, legata alle specificità dei territori (ad esempio, su base
  regionale).

Il Modello individua le tipologie di amministrazioni che possono costituire dei
Tavoli di coordinamento, sia su base tematica che territoriale:

- per coordinare l’erogazione dei servizi;

- per coinvolgere nuovi erogatori.

I Tavoli supportano a propria volta AGID nella promozione del Modello di
interoperabilità e delle sue indicazioni.

L’adesione al Catalogo avviene tramite la firma di una Convenzione tra l’ente e
AGID.

Per l’attuazione del Modello, AGID direttamente o indirettamente:

- realizza il Catalogo e definisce il processo di *onboarding*;

- verifica il rispetto delle regole del Modello quale condizione di accesso al
  Catalogo;

- stabilisce, pubblica e controlla le metriche di utilizzo e di qualità dei
  servizi;

- aggiorna costantemente il Modello stesso dal punto di vista tecnologico.

Le PA saranno responsabili della pubblicazione dei termini di utilizzo delle
Interfacce di servizio da loro esposte e del rispetto dei termini di servizio di
quelle fruite.

Obiettivi
---------

- Realizzare le azioni necessarie per il transito, in maniera coordinata, delle
  pubbliche amministrazioni, da SP-Coop al nuovo Modello di interoperabilità e
  favorire così l’armonizzazione delle scelte architetturali della Pubblica
  Amministrazione;

- creare le condizioni tecnologiche che favoriscano lo sviluppo, da parte di
  amministrazioni e imprese, di soluzioni applicative innovative orientate al
  cittadino, alle imprese e alla Pubblica Amministrazione e che abilitino
  l’utilizzo delle infrastrutture immateriali;

- in coerenza con il principio di *interoperability by design* definito nell’
  *eGovernment Action Plan* 2016 - 2020, promuovere l’adozione dell’approccio
  “*API first*”, indipendentemente dalla tecnologia REST o SOAP, al fine di
  favorire la separazione dei livelli di *back end* e *front end*, con logiche
  aperte e standard pubblici;

- semplificare le procedure di scambio di dati e servizi tra le pubbliche
  amministrazioni e, ove possibile, tra Pubblica Amministrazione e privati;

- privilegiare standard tecnologici aperti che soddisfino l’esigenza di
  assicurare le interazioni tra PA e di queste con i cittadini e le imprese;

- favorire l’implementazione delle interfacce di servizio in conformità alle
  Linee guida e promuovere la qualità dei servizi esposti dalla PA.

Linee di azione
---------------


.. _la11:

LA11 - Transizione dei servizi SP-Coop al nuovo Modello da parte delle PA
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Tempi**
  In corso

**Attori**
  PA, AGID

**Descrizione**
  Per le piattaforme esistenti e per le attività progettuali in corso, le PA
  seguono le indicazioni nelle `Linee guida per transitare al nuovo Modello di
  interoperabilità
  <https://www.agid.gov.it/sites/default/files/repository_files/upload_avvisi/linee_guida_passaggio_nuovo_modello_interoperabilita.pdf>`__
  emanate da AGID con Determina 219/2017. Per dismettere SP-Coop, di specie le
  porte di dominio (PdD) in esso previste, le PA erogatrici predispongono un
  “piano di interfacciamento diretto” per assicurare l’accesso ai servizi
  attualmente in produzione. Nell’allegato 3 “Indicazioni operative per la
  migrazione dei servizi SP-Coop” sono riportate le indicazioni operative per la
  predisposizione dei citati piani. AGID pubblica le pianificazioni ricevute
  sul proprio sito istituzionale. Questo consente alle PA di pianificare:

  - i tempi per reindirizzare i sistemi che fruiscono di servizi attualmente in
    produzione verso le predisposte Interfacce di servizio con accesso diretto;

  - la data di definitiva dismissione delle porte di dominio, anch’essa da
    comunicare all’AGID.

  Qualora il servizio di una PA erogatrice all’interno del dominio SP-Coop debba
  essere fruito da una nuova entità senza Porte di dominio, l’interfacciamento
  diretto deve essere previsto con tempi compatibili con le necessità del nuovo
  fruitore.

**Risultati**
  Le PA erogatrici di servizi predispongono e inviano ad AGID i “piani di
  interfacciamento diretto” (entro aprile 2019).

  AGID pubblica le pianificazioni ricevute sul proprio sito istituzionale (entro
  giugno 2019).

**Aree di intervento**
  Nel breve periodo, impatto sulle PA.


.. _la12:

LA12 - Adozione delle linee guida del nuovo Modello di interoperabilità
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Tempi**
  In corso

**Attori**
  AGID, PA, Gestori di servizi pubblici e società a controllo pubblico

**Descrizione**
  Emanazione delle Linee guida del Modello di interoperabilità per le pubbliche
  amministrazioni e gli altri soggetti interessati (cittadini e imprese). Le
  Linee guida individuano gli standard tecnologici e le modalità di utilizzo da
  parte delle PA. Le PA realizzano le Interfacce di servizio per abilitare la
  comunicazione tra i sistemi informatici della PA e di questi con cittadini ed
  imprese. Le Linee guida sono costituite da:

  - presentazione del Modello di Interoperabilità 2018;

  - tecnologie e approcci all’Integrazione e Interoperabilità;

  - *pattern* e profili di interoperabilità;

  - *governance* del Modello di interoperabilità;

  - registri e Cataloghi.

  I documenti sopra elencati sono messi in consultazione pubblica, favorendo la
  consapevolezza delle PA sul nuovo modello. A chiusura della fase di
  consultazione, le Linee guida seguiranno le modalità di emanazione previste
  dall’articolo 71 comma 1 del CAD.

**Risultati**
  AGID pubblica in consultazione i documenti che costituiscono le Linee guida
  del Modello di interoperabilità (entro giugno 2019).

  Le PA adottano le Linee guida a completamento del processo di emanazione.

**Aree di intervento**
  Nel breve periodo, impatto sulle PA.


.. _la13:

LA13 - Realizzazione e popolamento del “Catalogo delle Interfacce di Servizio"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Tempi**
  Da dicembre 2019

**Attori**
  AGID, PA

**Descrizione**
  AGID realizza il “Catalogo delle Interfacce di servizio” che consente la
  condivisione delle Interfacce di servizio realizzate dalla PA. AGID definisce
  le modalità per la gestione del Catalogo, che tiene conto:

  - della specificità dei territori e dei diversi ambiti entro cui la PA opera;

  - della necessità di evitare ridondanze e/o sovrapposizioni in termini di
    competenze e contenuti.

  Le PA, nell’attuazione delle regole del Modello di interoperabilità,
  implementano le proprie Interfacce di servizio e popolano il Catalogo, al fine
  di agevolarne l’utilizzo da parte degli sviluppatori.

**Risultati**
  AGID realizza la prima *release* del Catalogo (dicembre 2020).

  Le PA pubblicano le Interfacce di servizio (da gennaio 2021).

**Aree di intervento**
  Nel medio periodo impatto sulle PA e sulle imprese; nel lungo periodo, impatto
  sui cittadini.
