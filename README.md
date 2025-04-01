# 🚀 Rollup

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-14.x+-339933.svg?logo=node.js)
![Rollup](https://img.shields.io/badge/rollup-2.x-EC4A3F.svg?logo=rollup.js)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?logo=javascript)

A modern boilerplate for Node.js libraries with JavaScript and Rollup. Perfect for creating optimized JavaScript packages ready for distribution.

**Topics:** `node` `javascript` `rollup` `library` `npm-package` `bundler` `es-modules` `offline-first` `documentation`

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Project Setup](#-project-setup)
- [Development](#-development)
- [Build](#-build)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 📦 Optimized bundling with Rollup
- 🔍 JavaScript linting with ESLint
- 🎨 Code formatting with Prettier
- 🧪 Testing with Jest
- 📤 Support for ES Modules import/export
- 💾 100% offline functionality
- 🔄 Support for hot-reload during development
- 📊 Tools for documentation generation
- 🔧 Babel configuration for modern JavaScript

## 🗂️ Project Structure

```
bl-rollup-node-javascript/
├── dist/               # Output directory for the bundle
├── src/                # JavaScript source code
│   ├── index.js        # Main entry point
│   └── lib/            # Library modules and functionality
├── test/               # Test files
├── .eslintrc           # ESLint configuration
├── rollup.config.js    # Rollup configuration
├── jest.config.js      # Jest configuration
├── babel.config.js     # Babel configuration
└── package.json        # Project dependencies and scripts
```

## 🚀 Project Setup

### 📥 Install

```bash
$ pnpm install
```

## 🔧 Development

```bash
$ pnpm dev
```

## 📦 Build

```bash
$ pnpm build
```

## 📦 Package Managers

This project supports multiple package managers. Here's how to use each one:

### NPM

NPM is the default package manager for Node.js.

**Install NPM:**
```bash
# Included with Node.js installation
```

**Setup project with NPM:**
```bash
# Install dependencies
$ npm install

# Development mode
$ npm run dev

# Build the library
$ npm run build
```

**Key features:**
- 📚 Vast package ecosystem
- 🔒 Hierarchical node_modules structure
- 📋 Package.json for dependency management

### Yarn

Yarn is a fast, reliable, and secure alternative to NPM.

**Install Yarn:**
```bash
# Install using NPM
$ npm install -g yarn
```

**Setup project with Yarn:**
```bash
# Install dependencies
$ yarn

# Development mode
$ yarn dev

# Build the library
$ yarn build
```

**Key features:**
- ⚡ Faster installation speeds
- 📦 Offline caching
- 🔒 Better security with checksums
- 📋 yarn.lock for deterministic installations

### PNPM

PNPM is a disk-space efficient package manager.

**Install PNPM:**
```bash
# Install using NPM
$ npm install -g pnpm
```

**Setup project with PNPM:**
```bash
# Install dependencies
$ pnpm install

# Development mode
$ pnpm dev

# Build the library
$ pnpm build
```

**Key features:**
- 💾 Disk space savings through symlinks
- 🚀 Fast installation speeds
- 🔄 Content-addressable storage
- 📋 pnpm-lock.yaml for dependency lock

### Comparison

| Feature               | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Disk usage            | High    | High    | Low     |
| Installation speed    | Slow    | Fast    | Fastest |
| Parallel installations| Limited | Yes     | Yes     |
| Workspace support     | Limited | Good    | Best    |
| Offline mode          | Limited | Good    | Good    |
| Security              | Good    | Better  | Better  |

## 📚 Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [JavaScript MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Rollup Documentation](https://rollupjs.org/guide/en/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
