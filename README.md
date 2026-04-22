<div align="center">
  <img src="images/icon.png" alt="LabBook Logo" width="120" />
  <h1>LabBook</h1>
  <p><em>Gestione Avanzata degli Esperimenti di Laboratorio</em></p>
  
  [![Build Windows & macOS](https://github.com/Nekym19/labbookv2/actions/workflows/build.yml/badge.svg)](https://github.com/Nekym19/labbookv2/actions/workflows/build.yml)
  [![Version](https://img.shields.io/badge/version-1.7.4-blue.svg)]()
  [![React](https://img.shields.io/badge/React-19.2.0-61DAFB?logo=react&logoColor=black)]()
  [![Electron](https://img.shields.io/badge/Electron-40.8.0-47848F?logo=electron&logoColor=white)]()
  
  <p>
    <a href="#-features">Features</a> •
    <a href="#%EF%B8%8F-download-and-installation">Download</a> •
    <a href="#%EF%B8%8F-tech-stack">Stack</a> •
  </p>
</div>

---

## 🔬 Cos'è LabBook?
**LabBook** è un'applicazione desktop moderna e open-source progettata per ricercatori e biologi. Consente di organizzare, pianificare e esportare in tutta sicurezza i protocolli e gli esperimenti di laboratorio.

Abbandona i vecchi quaderni cartacei: LabBook salva i tuoi dati in locale offrendo privacy totale, garantendoti la possibilità di esportare protocolli, organizzare il congelatore (Freezer) o gestire colture cellulari tramite un'interfaccia intuitiva.

<br>

## ✨ Features

- 🧬 **Esperimenti Guidati**: Modelli pre-impostati per *Western Blot, ELISA, PCR, Cell Culture, Pulldown e Immunofluorescenza*.
- 📂 **Gestione Progetti**: Organizza e riunisci i tuoi esperimenti, inventario e fogli di calcolo sotto un singolo "Project".
- ❄️ **Mappa Congelatori (Freezer)**: Riproduce fedelmente la struttura dei rack e dei pozzetti per catalogare cellule o campioni fisici.
- 🧮 **Calcolatori Integrati**: Calcolo delle diluizioni, molarità, ematocitometro in tempo reale.
- 📄 **Esportazione Multi-Formato**: Esporta ogni esperimento in **PDF** pronto per la stampa o in file **.DOCX / .ZIP**. Generazione automatica di plate-maps!
- 🗄️ **Archivio Intelligente**: Mantieni l'app veloce comprimendo il database in file di archivio per esperimenti vecchi.
- 💻 **Sistema Cross-Platform**: Esperienza unificata su **Windows, macOS e Linux** con temi Chiaro e Scuro integrati e reattivi.

<br>

## ⬇️ Download and Installation

L'applicazione è automaticamente compilata per tutti i sistemi operativi principali ogni volta che viene rilasciata una nuova versione.

1. Visita la pagina delle **[Releases su GitHub](../../releases/latest)**.
2. Scarica il file adatto al tuo sistema:
   - 🪟 **Windows**: Scarica il file `.exe`.
   - 🍎 **macOS**: Scarica il file `.dmg` (scegli "arm64" se hai un Mac con processore M1/M2/M3, oppure "x64" per Intel).
   - 🐧 **Linux**: Scarica il file `.AppImage`.
3. Installa l'applicazione e lanciala!

<br>

## 🛠️ Tech Stack

LabBook è stato costruito utilizzando tecnologie web moderne impacchettate per desktop.
- **Frontend UI Framework**: [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Desktop Wrapper**: [Electron 40.8](https://www.electronjs.org/)
- **Document Generation**: `pdfmake` (per i PDF) e `docx` (per i documenti Word)
- **Design**: CSS Vanilla con variabili globali, Glassmorphism design system e Icone [Lucide](https://lucide.dev/).

<br>
---
<div align="center">
  <small>Creato con ❤️ per i Ricercatori.</small>
</div>
