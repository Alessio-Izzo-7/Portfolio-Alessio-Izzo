Questo è il mio primo sito web, progettato per rappresentare il mio lavoro come fotografo e web developer. Per realizzarlo, ho utilizzato HTML e CSS, scritti tramite SASS, creando un layout semplice ma accattivante, con l’obiettivo di rendere la navigazione intuitiva e stimolante per l'utente.

Per gestire il layout, ho scelto di impiegare classi predefinite, che mi hanno permesso di organizzare facilmente gli elementi senza dover applicare manualmente gli stili a ciascun componente. Questo approccio ha semplificato il processo di sviluppo, risparmiando tempo e rendendo il codice più ordinato e facile da mantenere. Grazie a questa struttura modulare, il sito è risultato anche completamente responsive, adattandosi perfettamente a dispositivi di diverse dimensioni e risoluzioni, garantendo un'esperienza di navigazione fluida su desktop, tablet e smartphone.
Il design del sito si basa su una palette di tre colori principali: arancione, nero e bianco. L’uso alternato e strategico di questi colori non solo crea un contrasto cromatico forte e visivamente interessante, ma aiuta anche a guidare l'utente attraverso le diverse sezioni del sito, migliorando la fruibilità. L’arancione, vivace e dinamico, attira l'attenzione sugli elementi chiave, mentre il nero e il bianco bilanciano il design, offrendo eleganza e leggibilità.

Per ottimizzare la gestione e la flessibilità del design, ho scelto di implementare i colori attraverso variabili CSS. Questa scelta non solo rende il codice più pulito e facilmente manutenibile, ma consente anche di modificare rapidamente la palette del sito in futuro, adattandola a eventuali cambiamenti estetici o alle esigenze specifiche del progetto senza dover intervenire manualmente su ogni singolo elemento.



Struttura delle Directory:
---
Cartella Principale
-Contiene i file HTML di tutte le pagine del sito.
File HTML: Ogni pagina del sito è rappresentata da un file HTML separato, che semplifica la gestione e gli aggiornamenti.

-Cartella Assets
  Questa cartella contiene tutti i file essenziali utilizzati nel sito, suddivisi in sotto-cartelle:
  
  - Cartella Download: Contiene i file che gli utenti possono scaricare, come il portfolio in formato PDF.
    
  - Cartella Img: Include tutte le immagini utilizzate nel sito, con una nomenclatura chiara che facilita il rintracciamento:
    Le immagini sono organizzate per sezione di riferimento (ad esempio, "Chi sono", "portfolio", ecc.) e nome del sito.
    
    -Cartella Sass:
    La cartella sass contiene tutti i file SCSS per gestire gli stili del sito. La struttura al suo interno è la seguente:  
      - Map: File di mappa che traccia i file CSS compilati per il debugging e la gestione del codice.
      - style.scss: Il file principale con le regole di stile per la Home page.
      - style.css: Il file CSS risultante dalla compilazione di style.scss, che viene caricato nel browser.
      - scss utilities: Un file che contiene il codice SCSS riutilizzato in tutte le pagine del sito per gestire layout, colori e animazioni CSS.
      -Cartelle per ogni pagina del sito: Per ogni pagina principale del sito è presente una cartella dedicata che contiene i relativi file SCSS.
        Questo approccio modulare garantisce una gestione più efficiente degli stili. Le cartelle sono le seguenti:
        - Contattami: Contiene gli stili SCSS per la pagina di contatto.
        - Portfolio: Include gli stili SCSS per la pagina Portfolio.
        - Curriculum Vitae: Contiene gli stili SCSS per la pagina del Curriculm.

Questa struttura modulare consente di mantenere il sito ben organizzato, facilmente aggiornabile e scalabile. Grazie a questa disposizione chiara delle cartelle, è possibile gestire rapidamente tutti i file e aggiornare il sito con facilità. La separazione delle risorse (immagini, file scaricabili, stili per ciascuna pagina) contribuisce a garantire una gestione efficiente e un progetto ben strutturato.
