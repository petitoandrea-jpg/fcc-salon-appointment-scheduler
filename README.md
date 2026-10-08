# fcc-salon-appointment-scheduler
Sviluppo di un'applicazione CLI interattiva per la gestione e prenotazione di appuntamenti in un salone di bellezza, interamente pilotata da terminale.

Caratteristiche principali:

Definizione dello schema PostgreSQL con tabelle correlate per clienti (customers), servizi offerti (services) e prenotazioni (appointments).

Implementazione di un menu interattivo in Bash che gestisce flussi condizionali (if/else, funzioni ricorsive) e prompt di input utente (read).

Logica di registrazione automatica per nuovi clienti se non presenti nel database, collegando dinamicamente la nuova chiave primaria generata (customer_id) all'appuntamento registrato.

Formattazione dell'output e sanitizzazione degli input per garantire query SQL pulite e prive di errori.
