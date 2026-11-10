# Clever Waste — web app demo

Questa è una prima ricostruzione interattiva del prototipo Figma `Clever Waste App.fig`.

## Come provarla

1. Estrai la cartella `clever-waste-web` dallo ZIP.
2. Apri `index.html` con Chrome, Safari o Edge.
3. L'app si apre dentro un iPhone virtuale fisso su sfondo nero.

Non richiede Node.js, React, npm o crediti Figma Make: è una web app statica HTML/CSS/JavaScript.

## Come pubblicarla su GitHub Pages

1. Accedi a GitHub e crea un repository nuovo chiamato `clever-waste-web`.
2. Estrai lo ZIP sul computer.
3. Carica **il contenuto** della cartella (index.html, app.js, styles.css e cartella assets) nella radice del repository.
4. Apri `Settings → Pages`.
5. In `Build and deployment`, scegli `Deploy from a branch`, branch `main`, cartella `/ (root)`, poi `Save`.
6. Attendi la pubblicazione: GitHub mostrerà il link del sito nella stessa sezione Pages.

## Cosa è interattivo in questa demo

### Area cliente
- Navigazione Home, Cerca, Offerte, Ordini, Profilo.
- Ricerca testuale e filtri per categoria.
- Schede prodotto e dettaglio offerta.
- Preferiti (salvati nel browser con localStorage).
- Scelta della quantità e simulazione della prenotazione.
- Ordini attivi/completati e codici di prenotazione demo.
- Pagine Risparmio, Clever Points, Premi, Livelli, Impatto e Preferenze.
- Modifica del nome demo del profilo.

### Area produttore
- Passaggio dall'area cliente all'area produttore.
- Panoramica, offerte, prenotazioni, scorte e profilo attività.
- Creazione simulata di una bozza offerta.
- Aggiornamento simulato delle scorte.
- Registrazione simulata di un acquisto.
- Report, dashboard e suggerimenti Clever Waste AI dimostrativi.

## Dati e limiti

- Prodotti, attività, prezzi, statistiche, disponibilità e prenotazioni sono dati dimostrativi.
- Le prenotazioni non inviano ordini a un esercente e non comportano pagamenti.
- L'area produttore non è collegata a un gestionale o a un magazzino reale.
- Clever Waste AI mostra insight simulati; non chiama un modello AI o sistemi di vendita reali.
- Dati demo di preferiti, ordini e nome profilo sono conservati solo nel browser corrente tramite `localStorage`.
- Questa prima versione ricostruisce le principali aree individuate nel file Figma e riutilizza le immagini incorporate. Non è ancora una conversione automatica 1:1 di ogni singolo frame, variante e collegamento del file `.fig`.

## Struttura

```text
clever-waste-web/
├── index.html
├── styles.css
├── app.js
├── README.md
└── assets/
    ├── dettaglio-offerta-riferimento.png
    └── figma/  (risorse immagine estratte dal file Figma)
```

## Personalizzazione

- Testi, prodotti, categorie e dati demo: `app.js`.
- Aspetto del telefono e layout responsive: `styles.css`.
- Immagini: `assets/figma/`.

Il file Figma originale non viene modificato.
