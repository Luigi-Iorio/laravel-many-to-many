# Laravel Boolfolio - Project Technology

Questo progetto è il proseguimento della repository precedente [laravel-one-to-many](https://github.com/Luigi-Iorio/laravel-one-to-many.git). In questa repo è stata aggiunta una nuova entità chiamata `Technology`.

### Descrizione

L'entità `Technology` rappresenta le tecnologie utilizzate (es: Html, Css, Js...) ed è in relazione many-to-many con i progetti.

Le principali funzionalità aggiunte a questo progetto sono:

-   Creazione della migration per la tabella `technologies`.
-   Creazione del model `Technology`.
-   Creazione della migration per la tabella pivot `project_technology`.
-   Aggiunta ai modelli `Technology` e `Project` dei metodi per definire la relazione many-to-many.
-   Visualizzazione delle tecnologie utilizzate, se presenti, nella pagina di dettaglio di un progetto.
-   Possibilità per l’utente di associare le tecnologie nella pagina di creazione e modifica di un progetto.
-   Gestione del salvataggio dell’associazione progetto-tecnologie con opportune regole di validazione.
-   Aggiunta delle operazioni CRUD per il model `Technology`, permettendo di gestire le tecnologie utilizzate nei progetti direttamente dal pannello di amministrazione.
-   Gestione delle immagini (view, create, update, delete).
