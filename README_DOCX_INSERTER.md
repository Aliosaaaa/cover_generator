# DOCX Image & Infographic Inserter AI

Software intelligente per l'inserimento automatico di immagini e infografiche in documenti DOCX, basato sull'analisi AI del contenuto.

## 🎯 Caratteristiche

- **Analisi Automatica Avanzata**: Analizza il tuo documento DOCX e identifica **1-8 opportunità visive per ogni capitolo** (garantito!)
- **AI Proattiva**: L'AI cerca attivamente concetti astratti, processi, dati, scene, metafore e momenti chiave da visualizzare
- **Suggerimenti Intelligenti**: 4 tipi di immagini (immagine, infografica, diagramma, grafico) con descrizioni dettagliate
- **Testo Perfetto nelle Immagini**: Prompt ottimizzati per generare testo perfettamente leggibile senza errori nelle infografiche e diagrammi
- **Controllo Totale**: Selezioni tu quali immagini generare con sistema di checkbox intuitivo
- **Generazione AI Professionale**: Usa Gemini 2.5 Flash Image Preview con prompt avanzati per qualità massima
- **Inserimento Automatico**: Le immagini vengono inserite nel documento nella posizione ottimale
- **Download DOCX**: Scarica il documento completo con tutte le immagini inserite

## 🚀 Come Usare

### 1. Configurazione Iniziale

1. Apri `docx-image-inserter.html` nel tuo browser
2. Inserisci la tua **API Key di Google Gemini**:
   - Ottieni una chiave gratuita su: https://aistudio.google.com/app/apikey
   - Clicca su "Salva Key"

### 2. Analisi del Documento

1. Clicca su "Seleziona file DOCX" e carica il tuo documento
2. Clicca su "⚡ Analizza Documento"
3. Attendi che l'AI analizzi il contenuto (può richiedere 30-60 secondi a seconda della lunghezza)

### 3. Review dei Suggerimenti

Dopo l'analisi vedrai un report organizzato per capitoli con:
- **Tipo di immagine** (immagine, infografica, diagramma, grafico)
- **Posizione suggerita** (inizio, metà, fine del capitolo)
- **Descrizione dettagliata** di cosa dovrebbe rappresentare
- **Motivo** per cui è necessaria
- **Testo da includere** (quando applicabile) - il testo esatto da inserire nell'immagine

**IMPORTANTE**: Ogni capitolo avrà **minimo 1 e massimo 8 suggerimenti** - l'AI è stata ottimizzata per essere proattiva!

Seleziona le immagini che vuoi generare usando le checkbox.

### 4. Generazione Immagini

1. Clicca su "🎨 Genera Immagini Selezionate"
2. Attendi la generazione (circa 5-10 secondi per immagine)
3. Visualizza il progresso in tempo reale

### 5. Download

1. Una volta completata la generazione, clicca su "💾 Download Documento DOCX"
2. Il documento verrà scaricato con tutte le immagini inserite

## 📋 Requisiti

- **Browser moderno** (Chrome, Firefox, Edge, Safari)
- **Connessione Internet** (per le chiamate API)
- **API Key Google Gemini** (gratuita)
- **File DOCX** da analizzare

## 🔧 Tecnologie Utilizzate

- **Mammoth.js**: Lettura e parsing di file DOCX
- **Docx.js**: Creazione e modifica di documenti DOCX
- **Google Gemini AI**:
  - `gemini-2.0-flash-exp`: Analisi del testo
  - `gemini-2.5-flash-image-preview`: Generazione immagini
- **TailwindCSS**: Styling dell'interfaccia

## 📝 Tipi di Immagini Supportati

1. **Immagine**: Fotografie o illustrazioni realistiche
2. **Infografica**: Rappresentazioni grafiche di dati o concetti
3. **Diagramma**: Schemi tecnici o diagrammi di flusso
4. **Grafico**: Grafici a barre, linee, torta, ecc.

## 🎨 Funzionalità Avanzate

### Selezione Multipla
- **Seleziona Tutto**: Seleziona tutti i suggerimenti
- **Deseleziona Tutto**: Rimuove tutte le selezioni

### Organizzazione per Capitoli
- I suggerimenti sono automaticamente organizzati per capitolo
- Ogni capitolo mostra solo le immagini rilevanti per quella sezione

### Rilevamento Automatico Capitoli
Il software rileva automaticamente i capitoli usando:
- Pattern "Capitolo X" o "Chapter X"
- Titoli Markdown (# Heading)
- Suddivisione automatica in sezioni per documenti senza capitoli espliciti

## ⚠️ Limitazioni Attuali

1. **Dimensione Documento**: Funziona meglio con documenti fino a 50 pagine
2. **Lingua**: Ottimizzato per l'italiano, ma supporta anche altre lingue
3. **Formattazione**: Il documento finale potrebbe perdere alcune formattazioni complesse
4. **Rate Limiting**: Google Gemini ha limiti di rate (automaticamente gestiti con retry)

## 💡 Suggerimenti per Migliori Risultati

1. **Struttura Chiara**: Usa titoli e capitoli ben definiti
2. **Contenuto Descrittivo**: Più il testo è dettagliato, migliori saranno i suggerimenti
3. **Review Manuale**: Controlla sempre i suggerimenti prima di generare
4. **Selezione Mirata**: Non generare tutte le immagini, seleziona solo quelle essenziali

## 🔒 Privacy e Sicurezza

- **API Key Locale**: La tua API key è salvata solo nel browser (localStorage)
- **Nessun Server**: Tutto funziona client-side, i tuoi documenti non vengono caricati su server esterni
- **Google API**: Il testo viene inviato solo a Google Gemini per l'analisi (vedi policy Google)

## 🐛 Troubleshooting

### "API Key non configurata"
→ Inserisci la tua API Key nella sezione in alto

### "Nessun capitolo trovato"
→ Il documento potrebbe non avere una struttura chiara. Prova ad aggiungere titoli

### "Errore durante la generazione"
→ Potrebbero esserci problemi di rate limiting. Attendi qualche secondo e riprova

### "Il documento sembra vuoto"
→ Assicurati che il file DOCX contenga testo leggibile

## 📞 Supporto

Per problemi o domande:
- GitHub Issues: [Link al repository]
- Email: [Il tuo contatto]

## 📜 Licenza

© 2025 AI OSHA × KARMA WRITERS

---

**Powered by Google Gemini AI**
