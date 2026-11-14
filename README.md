# Palestra Musicale 🎵

Applicazione leggera e gratuita per esercitarsi con scale maggiori, scale minori, intervalli ed ear training su smartphone e computer.

## Livelli delle scale
- **Base:** 7 toniche naturali.
- **Intermedia:** 11 toniche, comprese Si♭, Mi♭, Fa♯, Do♯.
- **Avanzata:** tutte le 15 tonalità maggiori tradizionali.
- **Esperto:** 6 tonalità maggiori teoriche che possono richiedere doppi accidenti.
- **Personalizzato:** scegli liberamente una o più delle 21 toniche disponibili; le selezioni rimangono memorizzate nel browser.

Le scale sono estratte in modo casuale, senza ripetizioni fino alla fine del giro delle toniche selezionate. I tasti delle note sono sempre mescolati.

## Altre caratteristiche
- Modalità per riconoscere gli intervalli; in Personalizzato le note iniziali sono tratte dalle toniche scelte.
- Nomi delle note italiani (Do Re Mi) o inglesi (C D E).
- Inserimento delle note esclusivamente con pulsanti.
- Supporto ai doppi diesis (♯♯) e doppi bemolli (♭♭) nei livelli Esperto e Personalizzato.
- Correzione ortografica e enarmonica, suggerimenti e statistiche salvate localmente nel browser.
- Nessun backend; le impostazioni dell'utente non sono caricate su un server.

## Il sito
https://superrickypedia.github.io/palestra-musicale/

## File
- `index.html` — interfaccia e logica
- `manifest.webmanifest` — dati della web app
- `sw.js` — supporto alla cache offline quando pubblicato su HTTPS
- `icon.svg` — icona

## Scale minori

La nuova modalità **Minori · percorso completo (3)** guida un blocco di esercizi su un'unica tonica:

1. Identificare la **relativa maggiore** (stessa armatura, terza minore sopra la tonica minore).
2. Completare la minore **naturale**.
3. Passare alla **armonica**, alzando la settima rispetto alla naturale.
4. Passare alla **melodica classica**: alzare sesta e settima in salita e usare la naturale in discesa.

Nella minore naturale, rispetto alla **maggiore parallela** (stessa tonica), terza, sesta e settima sono abbassate di un semitono. La relativa maggiore non va confusa con la parallela.

Le tre forme possono anche essere esercitate separatamente. La selezione delle toniche e le alterazioni doppie restano supportate. Gli esercizi sono completamente interattivi e senza tastiera virtuale.

## Ear Training
- Intervalli melodici ascoltabili e riascoltabili con numero e qualità da riconoscere.
- Timbri sintetizzati in locale: pianoforte, chitarra, violino e flauto; modalità casuale o ensemble.
- Volume interno regolabile. Nessun file audio esterno e nessun server necessario.

Tutte le funzionalità sono disponibili all'indirizzo pubblico del sito sopra indicato.
