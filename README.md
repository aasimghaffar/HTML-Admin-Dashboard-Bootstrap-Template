# CubixSol – Admin Dashboard

Welcome to the **CubixSol Admin Dashboard** repository built on Bootstrap 5.3.2 and modern Vanilla JavaScript (zero jQuery dependency).

---

## 📖 Table of Contents
- [1. Project Overview](#1-project-overview)
- [2. Statement of Work (SOW)](#2-statement-of-work-sow)
- [3. Technology Stack & Key Features](#3-technology-stack--key-features)
- [4. Project Directory Structure](#4-project-directory-structure)
- [5. Getting Started & Development Commands](#5-getting-started--development-commands)
- [6. Custom Branding Implementation](#6-custom-branding-implementation)

---

## 1. Project Overview

This repository provides a modular, production-ready frontend admin panel framework featuring:
- **Responsive Layouts:** Desktop, Tablet, and Mobile viewport support.
- **Theme Switcher Engine:** Light / Dark themes, LTR / RTL directionality, transparent themes, and dynamic primary/background color pickers.
- **137+ Pre-built HTML Views:** Dashboards, Ecommerce, Mail, Chat, File Manager, Task Manager, Full Calendar, Invoices, User Profiles, Auth Workflows, and UI Component Suites.

---

## 2. Statement of Work (SOW)

The comprehensive Statement of Work detailing technical scope, deliverables, architecture, milestone schedules, RACI matrix, and quality assurance standards is available in:
👉 **[SOW.md](file:///c:/Work/HTML-Admin-Dashboard-Bootstrap-Template/SOW.md)**

---

## 3. Technology Stack & Key Features

- **Core Framework:** Bootstrap `v5.3.2`
- **Styles Engine:** Sass / SCSS (`v1.52.1+`)
- **Scripting:** Vanilla JavaScript (ES6+, zero jQuery dependency)
- **Build Automation:** Gulp `v4.0.2` & BrowserSync
- **Charting & Data:** ApexCharts (`v3.37.0`), Chart.js (`v3.8.0`), ECharts (`v5.3.3`), DataTables (`v1.12.1`), Grid.js (`v5.1.0`)
- **Maps:** Leaflet (`v1.8.0`), jsVectorMap (`v1.4.5`), GMaps (`v0.4.25`)
- **Form Controls:** Choices.js, Flatpickr, Pickr Color Picker, Quill Editor, FilePond, Dropzone

---

## 4. Project Directory Structure

```
HTML-Admin-Dashboard-Bootstrap-Template/
├── Change-logs/
│   └── changelog_V.13.txt          # Version update log
├── Dependencies.txt                # Dependency inventory & version list
├── Documentation/                  # Developer guides and HTML documentation
├── HTML/                           # Application source and dist repository
│   ├── dist/                       # Compiled production distribution files
│   │   ├── assets/                 # Minified CSS, JS, fonts, images, plugins
│   │   └── html/                   # Standalone production HTML pages
│   ├── src/                        # Development source files
│   │   ├── assets/                 # Raw SCSS, custom JS scripts, images
│   │   └── html/                   # Source HTML templates & partials
│   ├── gulpfile.js                 # Gulp compilation tasks
│   └── package.json                # Project dependencies & build scripts
├── README.md                       # Main repository README (this file)
└── SOW.md                          # Statement of Work document
```

---

## 5. Getting Started & Development Commands

### Prerequisites
- Node.js (`v16+` or `v18+` LTS)
- NPM (`v8+`)

### Installation & Build Commands
```bash
# Navigate to the HTML project folder
cd HTML

# Install dependencies
npm install

# Launch local development server with live reload (Gulp + BrowserSync)
npm start

# Compile SCSS, bundle assets, and build production output to dist/
npm run build
```

---

## 6. Custom Branding Implementation

The UI has been branded for **CubixSol** across both `src/` and `dist/`:
- **Page Title Tag:** `CubixSol – Admin Dashboard` (shared `mainhead.html` partial and all standalone pages)
- **Meta Author:** `CubixSol`
- **Footer Brand:** `CubixSol` ([footer.html](HTML/src/html/partials/footer.html))
- **Logos:** `assets/images/brand-logos/` (replace the placeholder files with your own logo files, keeping the same file names)
- **Theme settings storage keys:** prefixed with `cubix` (e.g. `cubixMenu`, `cubixdarktheme`)
