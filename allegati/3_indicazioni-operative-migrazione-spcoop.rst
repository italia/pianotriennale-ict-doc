Allegato 3 - Indicazioni operative per la migrazione dei servizi SP-Coop
========================================================================

A3.1 Pianificazione
-------------------

Secondo quanto previsto dalle `Linee guida per transitare al nuovo modello di
interoperabilità
<https://www.agid.gov.it/sites/default/files/repository_files/upload_avvisi/linee_guida_passaggio_nuovo_modello_interoperabilita.pdf>`__,
le amministrazioni devono “*adeguare i loro sistemi e predisporli
all’interfacciamento diretto senza l’intermediazione della Porta di dominio
(PdD), permettendo quindi il successivo spegnimento della Porta*”.

**Tale adeguamento porterà ad una modalità di erogazione dei servizi attualmente
in produzione che sarà definitiva e vigente anche a seguito dell’introduzione
nel nuovo Modello di interoperabilità in corso di definizione.**

L’adeguamento di tutti i servizi renderà possibile la dismissione delle porte di
dominio attualmente operanti, che deve avvenire secondo lo schema sotto
riportato, messo in atto con il contributo di AGID.

1. Le amministrazioni devono preventivamente predisporre una pianificazione per
   l’adeguamento dei propri servizi erogati entro 3 mesi dalla pubblicazione del
   Piano Triennale 2019 - 2021. Tale pianificazione dovrà riportare i seguenti
   elementi:

  - l’elenco dei servizi erogati e dei sistemi fruitori attualmente in
    produzione;

  - per ciascun servizio erogato dovrà essere riportato:

  - l’elenco dei fruitori;

  - tipo di sicurezza adottato (vedi par. A3.2.2 Gestione degli accessi);

  - la data a partire dalla quale il servizio sarà disponibile in modalità
    diretta. Tale data dovrà decorrere entro 3 mesi dalla pianificazione.

  Le amministrazioni trasmettono la propria pianificazione all’Agenzia tramite i
  servizi che saranno resi disponibili sul sito istituzionale della stessa.

2. Sulla base delle pianificazioni comunicate dalle amministrazioni, l’Agenzia
   delinea la pianificazione globale per la migrazione delle porte di dominio.

3. Sulla base di queste informazioni le amministrazioni fruitrici di servizi
   potranno pianificare l’effettivo interfacciamento diretto dei servizi. A tal
   scopo ognuna di esse redigerà un piano di fruizione che conterrà:

   - l’elenco dei servizi fruiti attualmente in produzione;

   - per ciascun servizio fruito dovrà essere riportato:

     - amministrazione erogatrice;

     - la data entro la quale i fruitori dovranno utilizzare la modalità diretta
       sulla base degli interventi da effettuare sulle politiche di sicurezza
       (vedi par. A3.2.2 Gestione degli accessi), tale data non dovrà eccedere i
       5 mesi dalla data di pubblicazione del piano globale prodotto da AGID.

4. Man mano che si procede con l’adeguamento, le amministrazioni fruitrici
   confermano all’Agenzia l’avvenuta conclusione dei lavori in modo da dare a
   quest’ultima la possibilità di monitorare il processo di migrazione.

5. Ciascuna amministrazione erogatrice, una volta che tutti i fruitori abbiano
   adottato i servizi con interfacciamento diretto, potrà definitivamente
   dismettere la propria Porta di dominio. Le amministrazioni comunicano
   all’Agenzia l’avvenuta dismissione della Porta di dominio.

L’Agenzia assume quale referente per le amministrazioni il “Responsabile per la
transizione al digitale” (RTD), a tal fine si richiamano le amministrazioni a
provvedere, con ogni opportuna urgenza, alla individuazione del RTD preposto
all’Ufficio per la transizione al digitale e alla relativa registrazione
sull’Indice delle pubbliche amministrazioni (IPA).

A3.2 Indicazioni per le attività di migrazione dei servizi.
-----------------------------------------------------------

Secondo quanto previsto dalle Linee guida per transitare al nuovo modello di
interoperabilità la migrazione dei servizi attualmente forniti attraverso la
Porta di dominio deve essere effettuata garantendo:

- la sicurezza del canale di comunicazione;

- la corretta gestione degli accessi (autorizzazione alla fruizione del
  servizio);

- la tracciatura in sostituzione a quella operata dalla Porta di dominio.

Di seguito si approfondisce ciascuno dei suddetti punti riportando, a titolo di
esempio, delle possibili soluzioni implementative. Resta fermo il fatto che le
amministrazioni sono libere di adottare soluzioni diverse anche attraverso
l’impiego di piattaforme specializzate in grado di fornire le funzionalità
richieste.

A3.2.1 Sicurezza del canale
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Nella Porta di dominio la sicurezza di canale è garantita dall’utilizzo del
protocollo *http over TLS (https)*, attraverso l’utilizzo del certificato emesso
dalla CA spcoop.gov.it.

Rimossa la Porta di dominio le entità operanti il colloquio dovranno provvedere
alla creazione di canali sicuri utilizzando il protocollo TLS, almeno nella
versione 1.2, impiegando certificati di cui si dovranno dotare autonomamente. Si
precisa che i certificati utilizzati per la creazione del canale sicuro devono
essere emessi da una CA pubblica preferendo, ove possibile, l’impiego di
*Extended Validation Certificate*.

La scelta dei terminatori di canale è demandata all’Amministrazione che potrà
prevedere anche l’impiego di *reverse proxy* per tutti i servizi su cui
terminare i canali cifrati.

A3.2.2 Gestione degli accessi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In merito al tema della gestione degli accessi, come previsto dalle Linee guida
per transitare al nuovo modello di interoperabilità, “*le amministrazioni
erogatrici dovranno provvedere, tramite le proprie infrastrutture di gestione
degli accessi, all’autorizzazione delle richieste di servizio nei confronti
delle amministrazioni fruitrici*”.

Per l’eliminazione della porta di dominio è indicata la scelta della sola mutua
autenticazione di canale come sistema di autenticazione sulla base della quale
operare l’autorizzazione alla fruizione dei servizi, in quanto, i possibili casi
che si possono presentare sono:

- l’erogatore e il fruitore impiegano *WS-Security* senza l’intervento della
  Porta di dominio: l’esposizione diretta del servizio potrà continuare ad
  operare senza interventi;

- l’erogatore impiega *WS-Security* senza l’intervento della Porta di dominio,
  mentre il fruitore utilizza la Porta di dominio per la gestione della
  *WS-Security*: l’esposizione diretta del servizio potrà continuare ad operare
  senza interventi da parte dell’erogatore invece il fruitore dovrà effettuare
  un *refactoring* dell’aspetto di sicurezza del servizio finalizzato
  esclusivamente all’introduzione della gestione della *WS-Security*;

- l’erogatore e il fruitore impiegano *WS-Security* con l’intervento della Porta
  di dominio: l’utilizzo di TLS Mutua autenticazione da parte di ambedue
  permette l’esposizione diretta del servizio senza interventi;

- l’erogatore utilizza la Porta di dominio per la gestione della *WS-Security*,
  mentre il fruitore impiega *WS-Security* senza l’intervento della Porta di
  dominio: l’utilizzo di TLS Mutua autenticazione da parte di ambedue permette
  l’esposizione diretta del servizio senza interventi da parte dell’erogatore
  invece il fruitore dovrà effettuare un *refactoring* dell’aspetto di sicurezza
  del servizio finalizzato esclusivamente alla eliminazione della gestione della
  *WS-Security*;

- l’erogatore e il fruitore implementano l’autenticazione/autorizzazione
  attraverso la sicurezza di canale: mediante l’uso di TLS Mutua autenticazione
  gestita dalla Porta di dominio, potranno continuare ad operare configurando la
  mutua autenticazione sugli applicativi.

Nei precedenti punti si è indicato con “*refactoring* dell’aspetto di sicurezza
del servizio”, l’insieme delle attività minime necessarie ad una amministrazione
fruitrice di un servizio per preservare la comunicazione con l’erogatore che
prevede, a seconda dei casi, l’aggiunta o l’eliminazione della gestione della
*WS-Security* al servizio.

La seguente tabella sintetizza quanto descritto in precedenza.

+---------------------------+-----------------------------+--------------------------+-----------------------------+
| **Scenario con Porta di dominio (ex ante migrazione)**  | **Scenario interfacciamento diretto (post migrazione)**|
+===========================+=============================+===========================+============================+
| **EROGATORE**             | **FRUITORE**                | **EROGATORE**             | **FRUITORE**               |
+---------------------------+-----------------------------+---------------------------+----------------------------+
| *WS-Security* su servizio | *WS-Security* su servizio   | Nessun intervento         | Nessun intervento          |
+---------------------------+-----------------------------+---------------------------+----------------------------+
| *WS-Security* su servizio | *WS-Security* su PdD        | Nessun intervento         | Intervento FRUITORE per    |
|                           |                             |                           | aggiungere *WS-Security*   |
+---------------------------+-----------------------------+---------------------------+----------------------------+
| *WS-Security* su PdD      | *WS-Security* su servizio   | TLS Mutua autenticazione  | Intervento FRUITORE per    |
|                           |                             |                           | eliminare *WS-Security*    |
|                           |                             |                           |                            |
|                           |                             |                           | TLS Mutua autenticazione   |
+---------------------------+-----------------------------+---------------------------+----------------------------+
| *WS-Security* su PdD      | *WS-Security* su PdD        | TLS Mutua autenticazione  | TLS Mutua autenticazione   |
+---------------------------+-----------------------------+---------------------------+----------------------------+
| TLS Mutua autenticazione  | TLS Mutua autenticazione su | TLS Mutua autenticazione  | TLS Mutua autenticazione   |
| su PdD                    | PdD                         |                           |                            |
+---------------------------+-----------------------------+---------------------------+----------------------------+

*Tabella A3.1 - Casi di autorizzazione alla fruizione di servizi*

Quanto indicato in precedenza con “TLS Mutua autenticazione”, per realizzare
l’autenticazione del fruitore è necessario che l’erogatore, una volta instaurata
una connessione in mutua autenticazione in http over TLS (https) attraverso
l’uso di certificati X509 V3, provveda a:

1. estrarre il DN (*Distinguish Name*) dal certificato utilizzato
   nell’*handshake* del TLS relativo all’amministrazione fruitrice;

2. estrarre il riferimento al servizio richiamato;

3. verificare se il fruitore, identificato dal DN, è autorizzato ad accedere al
   servizio.

A3.2.3 Tracciature
~~~~~~~~~~~~~~~~~~

In merito al tema della gestione delle tracciature, come previsto dalle Linee
guida per transitare al nuovo modello di interoperabilità”, si dovranno
riportare i seguenti elementi minimi:

- data e ora della richiesta;

- entità richiedente il servizio;

- servizio richiesto;

- esito della chiamata (autorizzata/rigettata).

È sufficiente che l’amministrazione ritrovi e illustri, con apposita
documentazione, le modalità adottate dalle piattaforme di erogazione utilizzate
per tracciare le informazioni richieste. Un approccio alternativo richiederebbe
che le amministrazioni provvedano alla realizzazione di componenti per la
gestione della tracciatura.

La tracciatura potrà poi riportare eventuali altre informazioni peculiari al
tipo di servizio erogato (tracciatura applicativa).

A3.2.4 Esempio
~~~~~~~~~~~~~~

A titolo di esempio, nel listato rappresentato qui di seguito si riporta uno
*skeleton* di codice per una possibile implementazione della gestione degli
accessi e tracciatura, realizzato in ambiente JEE - JSR 53: Java Servlet 2.3
Specification.

.. code-block:: java

   public class ReadX509ClientCertFilter implements Filter {
     public void init(FilterConfig fConfig) throws ServletException {}
     public void destroy() {}

     private class EntitaRichiedente {
       String subjectDN;
       String issuerDN;

       public EntitaRichiedente(String subjectDN, String issuerDN) {
         super();
         this.subjectDN = subjectDN;
         this.issuerDN = issuerDN;
       }

       @Override
       public String toString() {
         return "EntitaRichiedente [subjectDN=" + subjectDN + ", issuerDN=" + issuerDN + "]";
       }
     }

     public void doFilter(ServletRequest request,
       ServletResponse response,
       FilterChain chain) throws IOException, ServletException {
       /*
        * Recupero elementi:
        * - data e ora della richiesta;
        * - entità richiedente il servizio;
        * - servizio richiesto;
        * - esito della chiamata (autorizzata/rigettata).
        */

       LocalDate dataOraRichiesta = LocalDate.now();
       EntitaRichiedente entitaRichiedente = getEntitaRichiedente(request);
       String servizioRichiesto = getServizioRichiesto(request);
       boolean esitoChiamata = checkAuth(entitaRichiedente,servizioRichiesto);
       traceRequest(dataOraRichiesta,entitaRichiedente,servizioRichiesto,esitoChiamata);
       chain.doFilter(request, response);
     }

     private void traceRequest(LocalDate dataOraRichiesta,EntitaRichiedente entitaRichiedente,
       String servizioRichiesto,boolean esitoChiamata) {
       // TODO Implementare Gestione della tracciatura
       /*
        * Ad esempio utilizzando un file di log dedicato per rendere persistenti le tracce
        */
     }

     private boolean checkAuth(EntitaRichiedente entitaRichiedente, String servizioRichiesto) {
       // TODO Implementare gestione degli accessi
       return true;
       /*
        * Ad esempio verificare l’esistenza della coppia
        * entitaRichiedente/servizioRichiesto su wallet di credenziali (LDAP, DBMS, ...)
        */
     }

     private EntitaRichiedente getEntitaRichiedente(ServletRequest request) {
       X509Certificate[] certs = (X509Certificate[])
       request.getAttribute("javax.servlet.request.X509Certificate");
       if (null != certs && certs.length > 0) {
         return new EntitaRichiedente(
           certs[0].getSubjectDN().getName(),
           certs[0].getIssuerDN().getName()
         );
       } else {
         throw new RuntimeException("No X.509 client certificate found in request");
       }
     }

     private String getServizioRichiesto(ServletRequest request) {
       return request.getScheme() + "://" +
       request.getServerName() + ":" +
       ((HttpServletRequest)request).getRequestURI();
     }
   }
