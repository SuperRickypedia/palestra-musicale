# Palestra Musicale 🎵

Web app leggera per esercitarsi con la teoria musicale, utilizzabile da smartphone e computer.

## Funzioni
- Completa le scale maggiori scegliendo le note dai pulsanti (niente tastiera virtuale).
- Riconosci gli intervalli fra due note.
- Scegli i nomi italiani (**Do Re Mi**) o internazionali (**C D E**).
- Tre difficoltà: Base (pulsanti ordinati), Intermedio e Completo (pulsanti mescolati).
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
Il repository è **privato**. Non è stato attivato alcun sito pubblico e gli amici non possono ancora usare l'app tramite un URL. Per condividerla servirà scegliere un hosting statico o una modalità di pubblicazione. Non sono richiesti account per gli utenti finali.

Le statistiche restano nel browser e non vengono inviate a un server.
