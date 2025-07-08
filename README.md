# SmartReader

## Analisi

Avevo in mente di realizzare una semplice applicazione che permetta di leggere dei file testuali, come PDF, markdown, word e così via e dopo averli "scannerizzati" parola per parola 
io abbia la possibilità di: 

1. [cercare i sinonimi](#3-ricerca-sinonimi-e-contrari)
2. [cercare i contrari](#3-ricerca-sinonimi-e-contrari)
3. [spiegare il significato di una frase](#4-spiegazione-e-parafrasi-di-una-frase)
4. [fornire modi diversi per riscrivere la stessa frase](#4-spiegazione-e-parafrasi-di-una-frase)
5. [aggiungere delle note a bordo pagina con dei riferimenti alla singola parola o al paragrafo](#5-note)
6. [mostrare l'origine e l'etimologia delle parole](#6-origine-ed-etimologia-parole)

Oltre a questo nell'app dovrà esserci una lista dei file aperti, con la possibilità di rimuoverli, così da rendere l'esperienza più piacevole e fluida.

## Progettazione

### 1. Caricamento file

Verrà utilizzato il percorso specifico per individuare il file da leggere, questo permetterà una maggiore velocità per il caricamento, ma anche una minore flessibilità in quanto se venisse
spostato il file non sarebbe più leggibile.

Per la persistenza della leggibilità dei file verrà semplicemente creato un file di testo nella cartella principale del progetto con i percorsi dei file testuali, con possibilità di:
- modificare il percoso
- cancellare il percorso e quindi anche il riferimento al testo

### 2. Lettura dei file

Il programma dovrà dunque leggere i file testuali e al click di una singola parola o frase dovrà spuntare un menù a tendina stile pop-up con le funzionalità citate sopra. 

In base alla opzione scelta dall'utente verranno restituiti diversi dati sempre cone pop-up al di sopra della parola / frase.

### 3. Ricerca sinonimi e contrari

### 4. Spiegazione e parafrasi di una frase

### 5. Note

### 6. Origine ed etimologia parole