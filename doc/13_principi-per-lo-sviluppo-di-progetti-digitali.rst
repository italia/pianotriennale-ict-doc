Principi per lo sviluppo di progetti digitali
=============================================

Questo capitolo contiene principi che vengono qui ricordati e
raccomandati perché ritenuti fondamentali per la realizzazione dei
progetti contenuti nel Piano. Gli accorgimenti sono sia di natura
pratica - per la gestione del progetto - sia di natura contrattuale e
amministrativa per la stesura del contratto, la definizione degli
obiettivi, e l’approvvigionamento delle risorse.

Infine, la predisposizione di un progetto digitale per la realizzazione
di un nuovo sistema o per l’evoluzione di un sistema esistente,
richiede:

-  un chiaro disegno di cosa si vuole ottenere (design);

-  un piano di come costruirlo (realizzazione);

-  una strategia per portarlo all’adozione degli utenti finali (lancio);

-  **un piano per mantenere il sistema aggiornato**, sicuro, e utile nel
   tempo, oltre che per assicurarne il continuo funzionamento anche in
   caso di malfunzionamenti o disastri **(evoluzione e manutenzione)**.

Nei paragrafi seguenti si descrivono questi punti in maggior dettaglio.

Design del progetto
-------------------

La fase di design è essenziale per la buona riuscita del progetto. A
tale proposito, si rinvia al capitolo *Service design* delle Linee guida
di design per i servizi web della PA [102]_. In particolare, in fase di
progettazione dei servizi si raccomanda di:

1. **Coinvolgere sempre i cittadini, a partire dalla comprensione dei
   loro bisogni (Strategia n°1 delle Linee guida).** Questo vuol dire
   immaginare come il cittadino (o l’utente finale) andrà a utilizzare
   il sistema e fare in modo che tutte le funzionalità siano disegnate
   intorno alle sue esigenze, consentendogli di ottenere facilmente e
   rapidamente ciò di cui ha bisogno - senza inutili passaggi, e con
   istruzioni comprensibili a chiunque.

2. **Studiare per capire, documentare per non ripetere (Strategia n°3
   delle Linee guida).** È necessario conoscere il contesto nel quale
   opererà un progetto, definirne gli obiettivi, attenersi agli standard
   e fare ricerche su eventuali alternative valide a livello nazionale e
   internazionale, oltre che sulla disponibilità di strumenti e processi
   già sperimentati con successo che possono essere riutilizzati. Ogni
   fase di sviluppo del progetto deve essere documentata e resa
   disponibile in maniera aperta, da una parte per garantirne
   l’integrità e la sostenibilità futura, dall’altra per consentire
   possibili collaborazioni che potrebbero di aggiungervi nuovo valore.

3. **Applicare il principio once only (Strategia n°6 delle Linee
   guida).** Evitare che i cittadini debbano fornire le stesse
   informazioni più di una volta. Ogni processo deve essere pensato per
   essere quanto più semplice e usabile possibile, sostituendo le
   vecchie procedure quando necessario.

4. **Individuare obiettivi e metriche.** È necessario quindi individuare
   gli obiettivi da raggiungere, in termini di funzionalità e processi,
   insieme alle metriche in grado di valutare il successo e il
   gradimento del progetto. Ad esempio, in un sistema di fatturazione
   elettronica, un obiettivo potrebbe essere quello di “avere un
   processo per cui non è mai necessario stampare fatture”. Quando
   possibile, si raccomanda di usare metriche oggettive piuttosto che
   dati ricavati da questionari o rilevazioni. Ad esempio, considerando
   il “numero di fatture stampate tradizionalmente” come un indicatore
   di inadeguatezza del sistema o il “numero di fatture inviate
   elettronicamente” come fattore di successo.

5. **Partire dai dati (Strategia n°4 delle Linee Guida)**. Per prendere
   decisioni basate su comportamenti e dati reali è necessario
   realizzare servizi e processi interamente digitali, non limitandosi
   alla semplice trasposizione on line di un processo erogato in
   modalità tradizionale.

6. **Nominare un product owner**, ovvero una persona che -
   preferibilmente all’interno della PA e comunque non legata al
   soggetto che realizzerà il prodotto - sappia rappresentare le
   aspettative e i bisogni degli utenti finali del servizio progettato e
   che abbia una chiara competenza sui processi che si vuole
   digitalizzare e del risultato che si vuole ottenere. Ad esempio, in
   un progetto di fatturazione elettronica, il *product owner* sarà una
   persona che conosce bene i processi di fatturazione e sarà in grado
   di guidare gli esecutori del progetto fornendo consigli e indicazioni
   su come inviare e processare tali fatture, i dati che queste devono
   contenere, ecc.

Realizzazione del progetto
---------------------------

Oltre a seguire le Linee guida di design per i servizi web della PA, nel
produrre un piano sulle modalità di realizzazione del progetto, si
raccomanda alla PA di:

1. **Nominare un Technical Project Manager**, ovvero una persona
   che, all’interno dell’ente o comunque non legata all’impresa che
   realizzerà il prodotto, abbia forti competenze sulle tecnologie che
   andranno ad essere utilizzate e sia in grado di verificare la qualità
   del lavoro, aiutando nel coordinare le attività. Questa figura può
   essere individuata nel direttore dell’esecuzione dei lavori previsto
   dal Codice degli appalti [103]_ o in un suo delegato.

2. **Definire un prodotto minimo utilizzabile dall’utente (MVP)** **e i
   passi incrementali** e successivi che consegneranno una ad una le
   funzionalità richieste, fino al completamento dei lavori,
   possibilmente utilizzando metodologie agili, come Figura 11 I
   corrispettivi dovuti ai fornitori verranno erogati solo ed
   esclusivamente al completamento e alla verifica di ciascuno di questi
   passi. Si raccomanda, inoltre, che il prodotto venga reso disponibile
   agli utenti in modalità sperimentale, senza aspettare il
   completamento di tutti i passi, al fine di individuare quanto prima
   eventuali problemi, criticità o fattori di rischio.

   Si suggerisce infine di prevedere, a livello contrattuale, che per
   arrivare al completamento del prodotto, questi passi possano subire
   variazioni in corso d’opera, in base ai risultati ottenuti e alle
   metriche di successo misurate.

Da un punto di vista tecnico inoltre occorre:

.. figure:: media/figura11.svg
   :width: 100%

   Figura 11 - Metodologia Agile Development


1. **Rendere i dati aperti, condividere processi e strumenti
   (Strategia n°8 delle Linee Guida).** Condividere ogni dato, ogni
   processo, ogni codice, ogni idea, ogni fallimento, ogni informazione
   è necessario e vitale per tutti i servizi, per favorire la
   trasparenza e la qualità nello sviluppo. Il codice e la
   documentazione di ogni servizio realizzato dalla Pubblica
   amministrazione dovrebbero essere rilasciati in formato aperto con
   una licenza adeguata per consentire un risparmio di costi e di tempo;
   laddove non fosse possibile, l’impedimento andrà adeguatamente
   motivato.

2. **Preferire componenti liberi o open source**, ovvero componenti
   software i cui codici sorgente siano disponibili e, se possibile,
   liberamente modificabili e adattabili alle esigenze della PA, come
   specificato all’articolo 68 del CAD. L’utilizzo di prodotti
   commerciali o i cui sorgenti sono chiusi dovrà essere puntualmente
   giustificato ed è consentito solo nel caso in cui il rapporto costo e
   funzionalità necessarie per il progetto sia più conveniente rispetto
   alle alternative *open source*.

3. **Scegliere soluzioni hardware in base a valutazioni di economicità
   ed efficienza**, in particolare valutando il costo di migrazione a
   soluzioni alternative (uscita dal *lock-in*) e garantendo la
   neutralità tecnologica.

4. **Avvalersi del cloud della PA**. Salvo comprovate ragioni
   tecniche, il software ed il progetto devono essere disegnati per
   essere utilizzati sul *cloud* della PA, come definito nel paragrafo
   3.1 “Data center e *cloud*\ ”.

Infine, il software realizzato deve:

1. **Essere strutturato in microservizi,** ovvero in componenti che
   svolgono poche funzionalità ben definite (ad es. verifica codice
   fiscale, esistenza dell’utente nella base di dati), controllate
   tramite API e facilmente riutilizzabili, in modo da poter essere
   messe a disposizione di altre PA tramite la *developer community*
   (cfr. capitolo 7 “Strumenti per la generazione e la diffusione di
   servizi digitali”).

2. **Esporre le API,** ovvero realizzare interfacce che consentano ai
   sistemi di comunicare e interagire tra di loro facilmente e in
   maniera automatica. L’interfaccia esposta all’utente e tutte le
   funzionalità del prodotto devono essere costruite attraverso l’uso di
   tali API (cfr. capitolo 5 “Modello di interoperabilità”).

3. **Utilizzare basi di dati** progettate secondo le regole esposte nel
   paragrafo 4.1 “Dati della PA” e, in particolare, inserire nel *Data &
   Analytics Framework* (DAF) [104]_ le informazioni in merito alla
   natura delle operazioni realizzate e alle loro mutazioni nel tempo.

4. **Mantenere l’interoperabilità** di dati, servizi e processi secondo
   le regole di interoperabilità e cooperazione dettate da AgID, fatti
   salvi i criteri necessari per garantire la privacy degli utenti. I
   dati devono essere resi disponibili come *open data* e devono essere
   accompagnati da un’esaustiva descrizione dei campi e del loro
   significato (metadati).

5. **Utilizzare solide strategie di testing e qualificazione,** ovvero
   utilizzare test di unità, test funzionali e *fuzz test* per
   verificare il codice ed effettuare *stress test* per verificare il
   carico che il prodotto sarà in grado di sostenere. Si consiglia
   inoltre l’utilizzo di strategie di analisi statica del codice, e
   l’auditing del risultato per affrontare i problemi relativi alla
   sicurezza.

6. **Utilizzare best practices di sicurezza** come, ad esempio,
   criptare le password e le comunicazioni via rete.

7. **Includere tutta la documentazione necessaria,** ovvero includere
   documentazione sulla struttura dei dati utilizzati (campi, tabelle,
   ecc.), sul funzionamento e l’utilizzo del software, nonché
   documentazione sul funzionamento del prodotto, su come mantenerlo,
   aggiornarlo e monitorarlo.

8. **Appartenere alla PA,** ovvero il contratto deve specificare che
   tutti i diritti sul prodotto realizzato, dal codice alla
   documentazione, dai nomi di dominio alle licenze, librerie di terze
   parti o brevetti registrati sul prodotto appartengono alla PA. In
   questo modo, la PA potrà continuare l’evoluzione del prodotto, anche
   avvalendosi di fornitori diversi da quelli che lo hanno sviluppato in
   origine.

9. **Essere messo a disposizione di altre PA,** ovvero registrato nel
   *market place* di Consip e, quando possibile, messo a disposizione
   liberamente completo di sorgenti e documentazione, con licenze aperte
   che ne consentano l’utilizzo, la modifica o l’evoluzione da parte di
   terzi.

Quando poi è importante l’integrazione del progetto con software
realizzati da terze parti o sistemi preesistenti, si consiglia di:

1. **Mettere a disposizione strumenti e infrastrutture di testing**,
   ovvero mettere a disposizione ambienti dove provare il proprio
   software, account di prova, o simulatori, utilizzabili liberamente da
   terze parti per verificare l’integrazione tra componenti.

2. **Utilizzare e** documentare processi per coordinare gli
   aggiornamenti software che prevedano dei meccanismi per annunciare il
   rilascio imminente di nuove versioni (newsletter, forum, …), il
   rilascio in ambienti di testing, e solo a seguito di verifica
   funzionale con gli utenti del sistema e software di terze parti in
   ambienti di testing, il rilascio in produzione.

1. **Mettere a disposizione librerie e kit di sviluppo**, ovvero esempi
   di codice e componenti software pronti per essere utilizzati da terze
   parti nei loro prodotti per integrarsi con i vostri sistemi. Questo
   facilita il riuso, migliora la qualità del codice, diminuisce i costi
   di manutenzione e aggiornamento, diminuisce significativamente il
   rischio di incompatibilità ed implementazioni non conformi alle
   specifiche, e diminuisce i costi di sviluppo per ognuna delle terze
   parti.

Lancio del progetto
-------------------

Nello stabilire un percorso per portare all’adozione del progetto, la PA
deve:

1. **Individuare la strategia di adozione di minor resistenza,** ovvero
   trovare il modo più semplice, veloce e con minore impatto perché il
   prodotto possa iniziare ad essere adottato, anche in forma limitata o
   incompleta. Anziché introdurre un grande cambiamento in un unico
   passo, è preferibile avanzare a piccoli passi incrementali -
   individualmente più semplici e meno rischiosi - verso il
   raggiungimento dell’obiettivo finale.

2. **Individuare una strategia di utilizzo incrementale,** ovvero
   trovare quei meccanismi che consentano l’adozione del prodotto, prima
   da parte di un numero ristretto di utenti, poi di un numero più ampio
   e, infine, da parte di tutti gli utenti. È importante evidenziare
   come il lancio di un servizio destinato alla totalità degli utenti
   non determini l’arresto delle attività di sviluppo o il completamento
   del prodotto. Al contrario, quando possibile, si raccomanda di
   individuare strategie che consentano di usare il prodotto ancor prima
   del suo completamento, al fine di individuare problemi, riorganizzare
   le priorità e iniziare a fornire i benefici derivanti
   dall’innovazione, seppure con un prodotto parziale.

3. **Individuare un piano per il lancio completo del prodotto,** ovvero
   per dismettere il prodotto precedente. Per progetti di grande
   dimensione, è importante evidenziare che una strategia di lancio può
   richiedere non solo la realizzazione del prodotto, ma campagne di
   promozione con gli utenti, meccanismi di comunicazione (mailing list,
   twitter, realizzazione di siti vetrina) e tutto ciò che è considerato
   importante per portare all’adozione del prodotto stesso.

4. **Comunicare efficacemente, spesso, ovunque (Strategia n°5 delle
   Linee Guida).** Le Pubbliche amministrazioni devono comunicare in
   maniera chiara l’utilità e i prerequisiti del servizio, oltre a tutte
   le informazioni relative alla protezione dei dati personali, alla
   tutela della vita privata e alla sicurezza informatica, raggiungendo
   i cittadini attraverso i canali di comunicazione più usati e diffusi,
   dando loro la possibilità di accedere ai propri dati, di controllarli
   e di correggerli, mantenendo un continuo dialogo, anche oltre e dopo
   il lancio del servizio.

Evoluzione e manutenzione del progetto
--------------------------------------

Nel definire le strategie per l’evoluzione e la manutenzione del
progetto, si raccomanda alla PA di:

1. **Assicurare la manutenzione e l’aggiornamento** periodico di tutti i
   software e i sistemi al fine di prevenire problematiche di sicurezza,
   garantire la compatibilità del software con nuove tecnologie e la
   conformità con l’evoluzione normativa.

2. **Assicurare un piano per la continua evoluzione del prodotto,**
   ovvero stabilire o avere una strategia per migliorare il prodotto
   dopo il lancio, aggiungere funzionalità, correggere problematiche e,
   più in generale, consentirne l’aggiornamento.

3. **Assicurare una strategia di disaster recovery e business
   continuity,** ovvero assicurarsi che, in caso di malfunzionamento o
   disastro, i dati critici non vengano persi e sia possibile continuare
   nell’erogazione dei servizi, seppur in modalità ridotta.

4. **Assicurare la continua verifica dei parametri di funzionamento,**
   come, ad esempio, il monitoraggio del software (errori, richieste,
   latenza), audit periodici per garantirne la sicurezza, ecc.

5. **Predisporre tutte le procedure necessarie per evitare il
   lock-in**, mantenendo aperta la possibilità di passare da un
   fornitore a un altro. L’utilizzo di diversi fornitori per la
   realizzazione, il mantenimento e il lancio del prodotto garantisce
   generalmente una migliore capacità di migrazione ad altro fornitore.

Progetti preesistenti
---------------------

Per i progetti preesistenti, ovvero per quelli relativi a soluzioni
digitali in fase di realizzazione o già in esercizio, sarà necessario
migrare gradualmente verso un approccio conforme alle indicazioni
riportate nel Piano, nei limiti imposti dai costi di adeguamento e dalla
riduzione dei costi di gestione.

.. rubric:: Note

.. [102]
   http://design.italia.it/linee-guida/service-design/

.. [103]
   Cfr. art. 101 del Codice degli appalti D.Lgs. 18 aprile 2016 n. 50.

.. [104]
   Cfr. capitolo 9 “Data & Analytics Framework”.
