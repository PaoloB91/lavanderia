# Lavanderia

Piccola web app personale per tenere le schede di lavaggio dei capi: foto, nome, se il capo perde colore, tipo di lavaggio, note.

Si apre da telefono su <https://paolob91.github.io/lavanderia/> e si aggiunge alla schermata Home (Condividi, "Aggiungi a Home"): da lì funziona come un'app, anche senza rete.

Un file HTML autocontenuto, nessuna libreria, nessun account, nessun server: **le schede e le foto restano nel telefono** (IndexedDB del browser). Qui online c'è solo il codice. Il backup si fa dall'app, dalle impostazioni: genera un file JSON con tutte le schede e le foto.
