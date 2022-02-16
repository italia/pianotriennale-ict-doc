CAPITOLO 5. Interoperabilità
============================

L’interoperabilità permette la collaborazione e l'interazione telematica
tra pubbliche amministrazioni, cittadini e imprese, favorendo
l’attuazione del principio\ *once only*\ e recependo le indicazioni
dell'\ `European Interoperability
Framework <https://joinup.ec.europa.eu/collection/nifo-national-interoperability-framework-observatory/european-interoperability-framework-detail>`__.

La Linea Guida sul Modello di Interoperabilità per la PA (di seguito
Linea Guida) individua gli standard e le loro modalità di utilizzo per
l’implementazione delle API favorendo:

-  l’aumento dell'interoperabilità tra PA e tra queste e
   cittadini/imprese;

-  la qualità e la sicurezza delle soluzioni realizzate;

-  la de-duplicazione e la co-creazione delle API.

La Linea Guida individua le tecnologie SOAP e REST da utilizzare per
l’implementazione delle API e, per esse, le modalità di loro utilizzo
attraverso l’individuazione di *pattern* e profili utilizzati dalle PA.

La Linea Guida è periodicamente aggiornata assicurando il confronto
continuo con:

-  le PA, per determinare le esigenze operative delle stesse;

-  i Paesi Membri dell’Unione Europea e gli organismi di
   standardizzazione, per agevolare la realizzazione di servizi digitali
   transfrontalieri.

Al fine di favorire la conoscenza e l’utilizzo del patrimonio
informativo detenuto dalle pubbliche amministrazioni e dai gestori di
servizi pubblici, nonché la condivisione dei dati che hanno diritto ad
accedervi, la Piattaforma Digitale Nazionale Dati rende possibile
l’interoperabilità dei sistemi informativi mediante l'accreditamento,
l'identificazione e la gestione dei livelli di autorizzazione dei
soggetti abilitati ad operare sulla stessa, nonché la raccolta e
conservazione delle informazioni relative agli accessi e alle
transazioni effettuate suo tramite.

Le PA nell’attuazione della Linea Guida devono esporre i propri servizi
tramite API conformi e registrarle sul catalogo delle API (di seguito
Catalogo) reso disponibile dalla Piattaforma Digitale Nazionale Dati, la
componente unica e centralizzata realizzata per favorire la ricerca e
l’utilizzo delle API. Una PA può delegare la gestione delle API
all’interno del Catalogo ad un’altra Amministrazione, denominata Ente
Capofila, relativamente a specifici contesti territoriali e/o ambiti
tematici.

Questo capitolo si concentra sul livello di interoperabilità tecnica e
si coordina con gli altri sui restanti livelli: `giuridico,
organizzativo e
semantico <https://joinup.ec.europa.eu/collection/nifo-national-interoperability-framework-observatory/3-interoperability-layers>`__.
Per l’interoperabilità semantica si consideri il capitolo “2. Dati” e
per le tematiche di sicurezza il capitolo "6. Sicurezza informatica".

Allo scopo di sviluppare servizi integrati e centrati sulle esigenze di
cittadini ed imprese, il Dipartimento per la Trasformazione Digitale
supporta le PA nell’adozione del Modello di Interoperabilità per la PA
direttamente e indirettamente pianificando e coordinando iniziative di
condivisione e accompagnamento per le pubbliche amministrazioni, anche
attraverso protocolli d'intesa ed accordi per:

-  la costituzione di tavoli e gruppi di lavoro;

-  l’avvio di progettualità congiunte;

-  la capitalizzazione delle soluzioni realizzate dalla PA in *open
   source* ecc.

Si tratta di iniziative di raccordo operativo per abilitare
l’interoperabilità tra le PA e per supportare:

1. la reingegnerizzazione dei processi e la digitalizzazione di
   procedure analogiche, la progettazione di nuovi sistemi e servizi;

2. il processo di diffusione e adozione delle piattaforme abilitanti di
   livello nazionale, nonché la razionalizzazione delle piattaforme
   esistenti;

3. la definizione delle specifiche tecniche di interoperabilità
   individuate per specifici domini di interoperabilità.

.. _contesto-normativo-e-strategico-4:

Contesto normativo e strategico
-------------------------------

In materia di interoperabilità esistono una serie di riferimenti sia
normativi che strategici a cui le amministrazioni devono attenersi. Di
seguito un elenco delle principali fonti. 

Riferimenti normativi italiani:

-  `Decreto legislativo 7 marzo 2005, n. 82 - Codice
   dell'amministrazione
   digitale <http://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2005-03-07;82!vig=>`__\ *(in
   breve CAD), artt. 12, 15, 50, 50-ter, 73, 75*

-  `Decreto legislativo 30 giugno 2003, n. 196 - Codice in materia di
   protezione dei dati
   personali <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2003-06-30;196!vig=>`__

-  Determina AGID 219/2017 - Approvazione e pubblicazione delle “Linee
   guida per transitare al nuovo modello di interoperabilità”

-  Determina AGID 406/2020 - Adozione della Circolare recante le linea
   di indirizzo sulla interoperabilità tecnica

-  `Piano Nazionale di Ripresa e Resilienza – Investimento 1.3: “Dati e
   interoperabilità” <https://italiadomani.gov.it/it/investimenti/dati-e-interoperabilita.html>`__

Riferimenti normativi europei:

-  `Regolamento (UE) 2016/679 del 27 aprile 2016 relativo alla
   protezione delle persone fisiche con riguardo al trattamento dei dati
   personali (in breve
   GDPR) <https://eur-lex.europa.eu/legal-content/IT/TXT/?qid=1584088833794&uri=CELEX:32016R0679>`__

-  `Regolamento (UE) 2014/910 del 23 luglio 2014 in materia di
   identificazione elettronica e servizi fiduciari per le transazioni
   elettroniche nel mercato interno (in breve
   eIDAS) <https://eur-lex.europa.eu/legal-content/IT/TXT/?qid=1584088967049&uri=CELEX:32014R0910>`__

-  `European Interoperability Framework – Implementation
   Strategy <https://eur-lex.europa.eu/legal-content/IT/TXT/?qid=1584086617794&uri=CELEX:52017DC0134>`__

-  `Interoperability solutions for public administrations, businesses
   and citizens <https://ec.europa.eu/isa2/eif_en>`__

.. _obiettivi-e-risultati-attesi-4:

Obiettivi e risultati attesi
----------------------------

OB.5.1 - Favorire l’applicazione della Linea guida sul Modello di
Interoperabilità da parte degli erogatori di API

-  R.A.5.1a -**Incremento del numero delle API presenti nel Catalogo -
   PDND**

-  

   -  `Baseline <https://monitoraggiopianotriennale.italia.it/interoperabilita/>`__\ `dicembre
      2020 <https://monitoraggiopianotriennale.italia.it/interoperabilita/>`__
      - 8 API presenti nel catalogo su Developers Italia.

   -  Target 2021 - 11 API presenti nel catalogo su Developers Italia.

   -  Target 2022 - 14 API presenti nel catalogo su Developers Italia.

   -  Target 2023 - 90 API registrate su Piattaforma Digitale Nazionale
      Dati.

-  R.A.5.1b -**Incremento del numero delle amministrazioni registrate
   nel Catalogo – PDND ed erogatrici di API**

-  

   -  `Baseline <https://monitoraggiopianotriennale.italia.it/interoperabilita/>`__\ `dicembre
      2020 <https://monitoraggiopianotriennale.italia.it/interoperabilita/>`__
      - 7 amministrazioni erogatrici registrate nel catalogo su
      Developers Italia.

   -  Target 2021 - 8 amministrazioni erogatrici presenti nel catalogo
      su Developers Italia.

   -  Target 2022 - 9 amministrazioni erogatrici presenti nel catalogo
      su Developers Italia.

   -  Target 2023 - 10 amministrazioni erogatrici registrati su
      Piattaforma Digitale Nazionale Dati.

OB.5.2 - Adottare API conformi al Modello di Interoperabilità 

-  R.A.5.2a -**Incremento del numero delle amministrazioni registrate
   sul Catalogo - PDND e fruitrici di API**

-  

   -  Target 2021 - n.d.

   -  Target 2022 - n.d.

   -  Target 2023 - 100 amministrazioni fruitrici registrati su
      Piattaforma Digitale Nazionale Dati.

-  R.A.5.2b -**Incremento del numero delle autorizzazioni realizzate ad
   API registrate sul Catalogo - PDND**

-  

   -  Target 2021 - n.d.

   -  Target 2022 - n.d.

   -  Target 2023 - *Baseline*: numero autorizzazioni rilasciate dalla
      Piattaforma Digitale Nazionale Dati.

OB.5.3 - Modelli e regole per l’erogazione integrata di servizi
interoperabili

-  R.A.5.3a - **Ampliamento del numero delle amministrazioni coinvolte
   nell’evoluzione della Linea guida sul Modello di Interoperabilità per
   la PA**

-  

   -  Target 2021 - n.d.

-  

   -  Target 2022 -*Baseline*: numero delle PA che evidenziano nuove
      esigenze applicative e partecipano alla definizione di pattern e
      profili di interoperabilità.

   -  Target 2023 - Incremento del 10% rispetto alla *baseline*.

.. _cosa-devono-fare-agid-e-dipartimento-per-la-trasformazione-digitale-1:

Cosa devono fare AGID e Dipartimento per la Trasformazione Digitale
-------------------------------------------------------------------

OB.5.1 - Favorire l’applicazione della Linea guida sul Modello di Interoperabilità da parte degli erogatori di API 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Le seguenti linee d’azione sono concluse:

-  **Settembre 2020 -**\ Emanazione Linea di indirizzo
   sull’interoperabilità tecnica per la PA - (AGID e Dipartimento per la
   Trasformazione Digitale) - **CAP5.LA01** 

Le seguenti linee d’azione devono concludersi entro:

-  **Gennaio 2022**- Emanazione Linea Guida sul Modello di
   Interoperabilità per la PA - (AGID) - **CAP5.LA02**

-  **Maggio 2022**-Emanazione Linea Guida sulla Piattaforma Digitale
   Nazionale Dati - (AGID) - **CAP5.LA09**

-  **Novembre 2022**-Prima revisione con l’aggiunta di nuovi *pattern*
   ai documenti operativi delle Lineaguida sulla base delle esigenze
   espresse dalle PA entro luglio 2022 - (AGID) - **CAP5.LA03**

-  **Dicembre 2022**- Lancio della Piattaforma Digitale Nazionale Dati
   comprensiva del Catalogo API implementata da PagoPA S.p.A. -
   (Dipartimento per la Trasformazione Digitale) - **CAP5.LA10**

-  **Maggio 2023**- Seconda revisione con l’aggiunta di nuovi *pattern*
   ai documenti operativi delle Linea guida sulla base delle esigenze
   espresse dalle PA entro novembre 2022 - (AGID) - **CAP5.LA04**

OB.5.2 - Adottare API conformi al Modello di Interoperabilità 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Le seguenti linee d’azione sono concluse:

-  **Dicembre 2020** - Implementazione strumenti per l’attuazione della
   Linea Guida sul Modello di Interoperabilità per la PA - (AGID) -
   **CAP5.LA07**

Le seguenti linee d’azione devono concludersi entro:

-  **Dicembre 2022 -** Raccolta preliminare delle API su
   Developers.italia.it - (Dipartimento per la Trasformazione Digitale)
   - **CAP5.LA06**

 **OB.5.3 - Modelli e regole per l’erogazione integrata di servizi interoperabili**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Le seguenti linee d’azione devono concludersi entro:

-  **Gennaio 2022** - Condivisione del modello evolutivo della Linea
   Guida sul Modello di Interoperabilità con PAC e Regioni - (AGID e
   Dipartimento per la Trasformazione Digitale) - **CAP5.LA11**

-  **Febbraio 2022** - Implementazione degli strumenti per la raccolta
   delle esigenze delle PA - (AGID) - **CAP5.LA12**

.. _cosa-devono-fare-le-pa-4:

Cosa devono fare le PA
----------------------

.. _ob.5.1---favorire-lapplicazione-della-linea-guida-sul-modello-di-interoperabilità-da-parte-degli-erogatori-di-api-1:

OB.5.1 - Favorire l’applicazione della Linea guida sul Modello di Interoperabilità da parte degli erogatori di API 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  **Da settembre 2020 (in corso)** - Le PA prendono visione della Linea
   di indirizzo sull’interoperabilità tecnica per la PA e programmano le
   azioni per trasformare i servizi per l’interazione con altre PA
   implementando API conformi - **CAP5.PA.LA01 **

-  **Da gennaio 2022** - Le PA adottano la Linea guida sul Modello di
   Interoperabilità per la PA realizzando API per l’interazione con
   altre PA e/o soggetti privati - **CAP5.PA.LA02**

.. _ob.5.2---adottare-api-conformi-al-modello-di-interoperabilità-1:

OB.5.2 - Adottare API conformi al Modello di Interoperabilità
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  **Da settembre 2020 (in corso)** - Le PA popolano gli strumenti su
   developers.italia.it con i servizi che hanno reso conformi alla Linea
   di indirizzo sull’interoperabilità tecnica - **CAP5.PA.LA03**

-  **Da dicembre 2022** - Le PA che hanno riportato su Developers Italia
   le proprie API provvedono al *porting* sul Catalogo delle API della
   Piattaforma Digitale Nazionale Dati - **CAP5.PA.LA07**

-  **Da gennaio 2023** - Le PA popolano il Catalogo con le API conformi
   alla Linea guida sul Modello di Interoperabilità per la PA -
   **CAP5.PA.LA04**

-  **Da gennaio 2023** - Le PA utilizzano le API presenti sul Catalogo -
   **CAP5.PA.LA05**

.. _ob.5.3---modelli-e-regole-per-lerogazione-integrata-di-servizi-interoperabili-1:

OB.5.3 - Modelli e regole per l’erogazione integrata di servizi interoperabili
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  **Da febbraio 2022** - Le PA evidenziano le esigenze che non trovano
   riscontro nella Linea guida e partecipano alla definizione di
   *pattern* e profilidi interoperabilità per l’aggiornamento delle
   stesse - **CAP5.PA.LA08**
