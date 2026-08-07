# Lavanderia

Piccola web app personale per tenere le schede di lavaggio dei capi: foto, nome, se il capo perde colore, tipo di lavaggio, note.

Si apre da telefono su <https://paolob91.github.io/lavanderia/> e si aggiunge alla schermata Home (Condividi, "Aggiungi a Home"): da lì funziona come un'app, anche senza rete.

Un file HTML autocontenuto, nessuna libreria, nessun framework: **le schede e le foto vivono nel telefono** (IndexedDB del browser). Qui online c'è solo il codice.

Opzionalmente l'app si collega a un repository GitHub privato dell'utente, dove copia una scheda per file a ogni salvataggio: serve a ritrovare tutto cambiando telefono. La chiave di accesso resta nel telefono e non compare da nessuna parte in questo codice. In alternativa (o in aggiunta) il backup si fa dalle impostazioni: un file JSON con tutte le schede e le foto.
