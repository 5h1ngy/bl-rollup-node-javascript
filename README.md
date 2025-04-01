# 🚀 Rollup

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-14.x+-339933.svg?logo=node.js)
![Rollup](https://img.shields.io/badge/rollup-2.x-EC4A3F.svg?logo=rollup.js)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?logo=javascript)

Un boilerplate per librerie Node.js con JavaScript e Rollup. Perfetto per creare pacchetti JavaScript ottimizzati e pronti per la distribuzione.

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Project Setup](#-project-setup)
- [Build](#-build)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 📦 Bundling ottimizzato con Rollup
- 🔍 JavaScript linting con ESLint
- 🎨 Formattazione del codice con Prettier
- 🧪 Testing con Jest
- 📤 Supporto per import/export ES Modules
- 💾 Funzionalità 100% offline
- 🔄 Supporto per hot-reload durante lo sviluppo
- 📊 Strumenti per generazione documentazione

## 🗂️ Project Structure

```
bl-rollup-node-javascript/
├── dist/               # Output directory per il bundle
├── src/                # Codice sorgente
│   ├── index.js        # Entry point principale
│   └── lib/            # Moduli e funzionalità della libreria
├── test/               # File di test
├── .eslintrc           # Configurazione ESLint
├── rollup.config.js    # Configurazione Rollup
├── jest.config.js      # Configurazione Jest
└── package.json        # Dipendenze e script del progetto
```

## 🚀 Project Setup

### 📥 Install

```bash
$ pnpm install
```

### 🔧 Development

```bash
$ pnpm dev
```

## 📦 Build

```bash
$ pnpm build
```

## 📦 Package Managers

Questo progetto supporta diversi package manager. Ecco come utilizzare ciascuno:

### NPM

NPM è il package manager predefinito per Node.js.

**Installazione NPM:**
```bash
# Incluso con l'installazione di Node.js
```

**Setup progetto con NPM:**
```bash
# Installazione dipendenze
$ npm install

# Build della libreria
$ npm run build
```

**Caratteristiche principali:**
- 📚 Vasto ecosistema di pacchetti
- 🔒 Struttura gerarchica di node_modules
- 📋 Package.json per la gestione delle dipendenze

### Yarn

Yarn è un'alternativa rapida, affidabile e sicura a NPM.

**Installazione Yarn:**
```bash
# Installazione tramite NPM
$ npm install -g yarn
```

**Setup progetto con Yarn:**
```bash
# Installazione dipendenze
$ yarn

# Build della libreria
$ yarn build
```

**Caratteristiche principali:**
- ⚡ Velocità di installazione superiore
- 📦 Caching offline
- 🔒 Maggiore sicurezza con checksum
- 📋 yarn.lock per installazioni deterministiche

### PNPM

PNPM è un package manager efficiente in termini di spazio su disco.

**Installazione PNPM:**
```bash
# Installazione tramite NPM
$ npm install -g pnpm
```

**Setup progetto con PNPM:**
```bash
# Installazione dipendenze
$ pnpm install

# Build della libreria
$ pnpm build
```

**Caratteristiche principali:**
- 💾 Risparmio di spazio su disco tramite symlink
- 🚀 Velocità di installazione elevata
- 🔄 Storage con indirizzamento basato sul contenuto
- 📋 pnpm-lock.yaml per blocco delle dipendenze

### Confronto

| Funzionalità          | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Utilizzo disco        | Alto    | Alto    | Basso   |
| Velocità installazione| Lenta   | Veloce  | Velocissima |
| Installazioni parallele| Limitato| Sì      | Sì      |
| Supporto workspaces   | Limitato| Buono   | Ottimo  |
| Modalità offline      | Limitato| Buono   | Buono   |
| Sicurezza             | Buona   | Migliore| Migliore|

## 📚 Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Rollup Documentation](https://rollupjs.org/guide/en/)
- [JavaScript MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
