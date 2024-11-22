# Discovery Step 5 – Selecting a Target


**punto 1 - 2:** abbiamo aggiornato l'initial mapping con i post - it nelle zone focus dei 3 UX - goal

**punto 3 -4:**

la parte della mappa che vogliamo analizzare è l' insieme dei seguenti task

     visualizzare catalogo e consigliati
     scegliere la lettura di maggior interesse
     visualizzare mappa dei negozi in cui viene venduto il titolo
     visualizzare le informazioni specifiche sui titoli  
     caricare i libri

Dalle interviste è emerso il bisogno da parte dei lettori esperti che bisogna avere un' interfaccia facile da utilizzare e capace di coinvolgere l'utente nell' uso del sistema, vogliamo concentrarci sull'analizzare questo bisogno.

**punto 5:**

si vuole analizzare lo user group dei **lettori esperti**

# Discovery step 6 - design Brief

|                                                    | description                                                                                                                                                                        |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **client/stakeholder**                             | Maria Francesca Costabile                                                                                                                                                          |
| **UCD sprint team**                                | Porcelli Andrea, Sgaramella Francesco, Sakellarides Elia, Zippo Fabio, Pontrelli Michele, Pacucci Niccolò                                                                          |
| **target user group**                              | lettore esperto                                                                                                                                                                    |
| **problem statement**                              | Attualmente non esiste un sistema efficente,efficacie e con alto grado di soddisfazione che riesce a fornire funzionalità di ricerca,esplorazione e confronto riguardo la lettura. |
| **design statement**                               | progettare un sistema che possa semplificare l'esperienza dei lettori tramite un interfaccia facile da usare                                                                       |
| **User's goal**                                    | avere uno strumento capace di consigliare letture interessanti e dare la possibilità di condividerla                                                                               |
| **UX goal**                                        | stimolare l'utente a conoscere nuove letture e fargli percepire un senso di calma e riflessione durante l'uso del sistema                                                          |
| **Deliverables**                                   | un applicazione capace di mettere in contatto i lettori fra di loro e coi negozi locali, stimulando e consigliando nuove letture                                                   |
| **constraints**                                    | /                                                                                                                                                                                  |
| **competitor**                                     | bookship, goodreads , library thing, litsy                                                                                                                                         |
| **design inspiration suggested by the user group** | TV Time, Just Watch, Pinterest, Splitwise, Dice, amazon, letterboxd,instagram e altri social networks                                                                              |


# DESIGN

# Design step 1 

**punti 1 - 3**:

Ognuno di noi ha analizzato una proposta dell'utente per un ottimo design, generando una lista di idee, da ogni lista abbiamo preso le **3 migliori**  per votazione generando la seguente tabella :

| **Persona**   | **Software/Contesto** | **Idea chiave**                    | **Descrizione**                                                                                                                                      |
| ------------- | --------------------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Francesco** | Letterbox             | **Design Essenziale**              | L’interfaccia è diretta e intuitiva, senza elementi discordanti, con punti principali subito visibili.                                               |
|               |                       | **Integrazione con Altri Servizi** | Connessione con altre piattaforme, come IMDb o servizi di streaming, per espandere l’uso e facilitare l’accesso a informazioni aggiuntive.           |
|               |                       | **Focus Comunitario**              | Commenti, like e condivisioni sono messi in evidenza per favorire l’interazione tra utenti.                                                          |
| **Michele**   | Amazon                | **Layout a Carosello**             | Caroselli visivi per presentare prodotti nuovi, consigliati o legati a eventi speciali.                                                              |
|               |                       | **Sistema di Recensioni**          | Valutazioni a stelle e sezione domande/risposte per offrire riassunti delle impressioni degli utenti e facilitare l’interazione.                     |
|               |                       | **Filtri di Ricerca Avanzata**     | Ricerca facilitata da filtri per data, autore, lunghezza, recensioni e livello di difficoltà del libro.                                              |
| **Elia**      | Zalando               | **Navigazione Veloce**             | Barra di ricerca avanzata con suggerimenti in tempo reale e filtri chiari che restringono i risultati.                                               |
|               |                       | **Semplicità e Usabilità**         | Struttura chiara e intuitiva con menù e filtri sempre accessibili, riducendo il sovraccarico cognitivo.                                              |
|               |                       | **Personalizzazione Intelligente** | Algoritmi per raccomandazioni su misura e dashboard organizzata con informazioni utili come acquisti e lista dei desideri.                           |
| **Porcelli**  | Instagram             | **Coinvolgimento Personalizzato**  | Algoritmi che personalizzano contenuti (es. feed e Reels) e Stories temporanee per incentivare il ritorno degli utenti.                              |
|               |                       | **Micro-interazioni**              | Feedback immediato con animazioni (es. cuore pulsante) e transizioni fluide per migliorare l’esperienza.                                             |
|               |                       | **Gamification e Socialità**       | Badge, metriche visibili e notifiche per incentivare attività; strumenti social come messaggi, visualizzazioni e commenti per stimolare interazioni. |

# Design step 2

**punto 1 - 2 - 3 :** 


1. Vuoi trovare un libro di tuo interesse , visualizza la sezione cataloghi e scegli il catalogo dei consigliati.
2. Dalla lista dei libri consigliati di un catalogo vuoi scegliere un libro da leggere seleziona quello che ti interessa.
3. Una volta selezionato il libro visualizza sulla mappa i punti vendita dove è disponibile.
4. Una volta trovato il libro di tuo interesse, visualizza le informazioni specifiche a riguardo.
5. Aggiungi un nuovo libro nella tua libreria personale.
6. Visualizza la tua libreria personale.


**punto 4 - 5**

- Pontrelli Michele - Task 1
- Zippo Fabio - Task 2
- Sgaramella Francesco - Task 3
- Sakellarides Elia - Task 4
- Porcelli Andrea- Task 5
- Pacucci Niccolò - Task 6



**Aggiungi un nuovo libro nella tua libreria personale [porcelli]**

1. **L'utente dal menu principale passa alla pagina per aggiungere un libro**  
   - Quando apri l’app, vai nel menu principale e scegli l’opzione “Aggiungi un nuovo libro”. Può essere un pulsante grande o un’icona con un simbolo “+”.

2. **Sceglie come vuole aggiungere il libro:**  
   - L’app ti dà varie opzioni per aggiungere il libro:  
     - **Scansione del codice a barre :** Usa la fotocamera del telefono per scansionare  "tipo scanner qr".
     - **Cerca il titolo o l’autore:** Scrivi il titolo del libro o il nome dell’autore nella barra di ricerca.  
     - **Importa da un servizio:** Se hai collegato un account come Kindle o Google Books, puoi aggiungere libri direttamente da lì.

3. **Aggiunge i dettagli personali:**  
   - Dopo aver selezionato il libro, puoi aggiungere informazioni personali, come:  
     - Tag o categorie (esempio: “Preferiti”, “Fantasy”).  
     - Lo stato del libro (Non letto, In lettura, Letto).

4. **Aggiunge altre note (opzionale):**  
   - Puoi anche scrivere qualcosa come:  
     - Dove hai preso il libro o quando.  
     - Pensieri personali.  
     - Note su dove sei arrivato nella lettura.

5. **Salva il libro:**  
   - Premi il pulsante “Salva” per confermare. L’app ti mostrerà un messaggio tipo: “Libro aggiunto con successo!”.  
   - Il libro ora si vede nella tua libreria personale.

6. **Guarda la sua libreria aggiornata:**  
   - Vai nella tua libreria per vedere il libro appena aggiunto. Puoi modificarlo o aggiungere altre informazioni quando vuoi.

# Design step 3

crazy 8 leggetelo e fatemi sapere se ci sono delle domande 

# Design step 4 - 5

molto intuitivi ditemi eventuali domande
