# Palestra Musicale 🎵

Web app leggera per esercitarsi con la teoria musicale, utilizzabile da smartphone e computer.

## Funzioni
- Completa le scale maggiori scegliendo le note dai pulsanti (niente tastiera virtuale).
- Riconosci gli intervalli fra due note.
- Scegli i nomi italiani (**Do Re Mi**) o internazionali (**C D E**).
- Tre difficoltà per le scale: Base (7 toniche naturali), Intermedia (le 7 + Si♭, Mi♭, Fa♯, Do♯), Avanzata (tutte le 15 tonalità maggiori tradizionali).
- Pulsanti delle note mescolati a ogni esercizio, in tutti i livelli; domande in ordine casuale senza ripetizioni fino al completamento delle tonalità del livello.
- Correzione anche della scrittura enarmonica, suggerimenti e statistiche salvate nel browser.

## Avvio
L'app è statica e non richiede backend, Python o dipendenze.
Per provarla su desktop, apri `index.html` in un browser.
Per aprirla su iPhone tramite un link, va distribuita su un indirizzo **HTTPS**: l'anteprima HTML dell'app File può bloccare JavaScript. Dopo il primo accesso HTTPS il service worker può memorizzare le risorse per l'uso offline.

## Struttura
- `index.html`: interfaccia, logica e stili inclusi
- `manifest.webmanifest`: metadati per l'installazione opzionale come app web
- `sw.js`: cache per utilizzo offline su HTTPS
- `icon.svg`: icona

## Privacy e pubblicazione
Il repository è pubblico e il sito è pubblicato via GitHub Pages all'indirizzo https://superrickypedia.github.io/palestra-musicale/. Non sono richiesti account per gli utenti finali.

Le statistiche restano nel browser e non vengono inviate a un server.
