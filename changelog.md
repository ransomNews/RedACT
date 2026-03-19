# Changelog

Tutte le modifiche rilevanti per ransomNews sono documentate in questo file.
Il formato è ispirato allo standard "Keep a Changelog" e mantiene un tracciamento chiaro e leggibile delle evoluzioni del progetto.

---

## [1.0.3] - 2026-03-18

### Aggiunto
- implementata suddivisione geografica automatica:
  - Nord Italia
  - Centro Italia
  - Sud Italia
  - Isole
  - Sconosciuta
- calcolo dinamico delle macro-aree basato sulle regioni presenti nei dataset
- aggiornamento automatico delle percentuali per ogni macro-area
- aggiunta funzione globale `recomputeDashboard()` per ricalcolo completo dati
- automatizzazione del footer:
  - data aggiornata automaticamente
  - versione gestita tramite variabile centralizzata
- aggiunta visualizzazione percentuale nei box geografici

### Modificato
- riorganizzazione layout HERO:
  - ridotta altezza del contenitore principale
  - migliorato allineamento tra blocco sinistro e destro
- ristrutturazione sezione TOP:
  - separazione in contenitore dedicato
  - aggiunta terzo box (nuovo contenitore)
- spostamento legenda impatto (Critico / Alto / Medio / Basso):
  - da area statistiche a intestazione tabella
  - integrazione visiva con sistema tab
- uniformazione completa tipografica UI:
  - allineati font, colori e pesi tra tab, legenda e intestazioni
- miglioramento ordinamento dinamico macro-aree (basato sui valori)
- aggiornamento struttura rendering dashboard:
  - sincronizzazione tra buildStats, buildTop5, buildGeoDivision e buildTrendChart

### Corretto
- risolto bug rendering grafico trend mensile (box vuoto)
- corretta posizione legenda (precedentemente non applicata)
- rimosso highlight grafico indesiderato su “Nord Italia”
- eliminati elementi residui:
  - "IN ATTESA"
  - "BOX NUOVO"
- corretta gestione aggregazione regioni (inclusa Valle d’Aosta e varianti)
- risolti problemi di coerenza tra totale dashboard e macro-aree
- sistemato allineamento elementi nella sezione HERO
- corretto comportamento di aggiornamento automatico dopo inserimento nuove rivendicazioni

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
