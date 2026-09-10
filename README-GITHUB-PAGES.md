# Raccolta Mesagne - PWA per GitHub Pages

La cartella `docs/` è pronta per essere copiata nella root del repository:

`https://github.com/Adramelech91/Raccolta_Mesagne`

## Pubblicazione

1. Copia la cartella `docs` nella root del repository, accanto alla cartella `app`.
2. Fai commit e push sul branch `master`.
3. Apri il repository su GitHub.
4. Vai in **Settings → Pages**.
5. In **Build and deployment / Source** scegli **Deploy from a branch**.
6. Seleziona:
   - Branch: `master`
   - Cartella: `/docs`
7. Premi **Save**.

Dopo pochi minuti la web app sarà disponibile normalmente a:

`https://adramelech91.github.io/Raccolta_Mesagne/`

## Cosa include

- calendario automatico da ieri ai successivi 5 giorni;
- evidenza di oggi e domani;
- alternanza del giovedì identica alla logica dell'app Android:
  - 1°, 3° e 5° giovedì: carta e cartone;
  - 2° e 4° giovedì: vetro e metalli;
- dettagli "si butta / non si butta" per ogni tipologia;
- tema chiaro, scuro o automatico;
- installazione come PWA;
- funzionamento offline dopo il primo caricamento;
- nessuna notifica e nessun backend.

## Aggiornamenti futuri

Quando modifichi file dentro `docs/`, GitHub Pages pubblicherà automaticamente la nuova versione.

Se cambi file già memorizzati offline, aumenta il numero di versione in `docs/sw.js`, ad esempio:

`raccolta-mesagne-v1.0.1`

così il service worker scarta la vecchia cache.
