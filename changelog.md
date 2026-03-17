# Changelog

Tutte le modifiche rilevanti per ransomNews sono documentate in questo file.
Il formato è ispirato allo standard "Keep a Changelog" e mantiene un tracciamento chiaro e leggibile delle evoluzioni del progetto.

---

## [1.0.2] - 2026-03-17

### Aggiunto
- implementata nuova scala colori basata sull’impatto dei dati pubblicati:
  - GRIGIO (0 – 9,99 GB) → basso impatto
  - GIALLO (10 – 49,99 GB) → medio
  - ARANCIONE (50 – 99,99 GB) → alto
  - ROSSO (≥ 100 GB) → critico
 
- aggiunta legenda colori (impatto attacco):
  - Critico / Alto / Medio / Basso
  - design uniforme con indicatori quadrati

### Modificato
- restyling grafico sezione TOP 5:
  - barre più pulite e leggibili
  - layout ottimizzato e coerente
- uniformati i nomi dei gruppi: tutti in minuscolo (standardizzazione dataset)
- aggiunto nuovo gruppo: bashe (mantenendo i dati storici separati)

### Corretto
- correzione gestione dati mancanti: valori vuoti ora impostati automaticamente a 0

---

## [1.0.1] - 2026-03-16

### Aggiunto
- miglioramenti funzionali all'esecuzione del codice interno HTML

### Modificato
- 

### Corretto
-

---

## [1.0.0] - 2026-03-12

### Aggiunto
- prima release pubblica della nuova dashboard in HTML (human maintained)
- deploy tramite GitHub Pages
- dashboard HTML statica per la visualizzazione delle rivendicazioni ransomware

### Modificato
- 

### Corretto
- 

---

## [0.1.0] - 2026-03-10

### Aggiunto
- struttura iniziale del repository
- cartella dataset per il tracciamento ransomware
- layout HTML di base

### Modificato
- 

### Corretto
- 
