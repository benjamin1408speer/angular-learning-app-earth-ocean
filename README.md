# Earth Ocean Learning App

## Description
Interactive web application for children to explore oceans, seas and marine ecosystems.

The app provides structured information about different water bodies, including biodiversity, depth and climate conditions.

## Technologies
- Angular
- TypeScript
- HTML / CSS

## Features
- Exploration of major oceans and seas
- Information about marine life and ecosystems
- Dynamic navigation with multiple routes
- Structured content presentation

## Purpose
This project was my first hands-on experience with Angular and frontend development.

It helped me understand component-based architecture, routing and structuring larger applications.

## Status
Completed (early project, demonstrates learning progress)
EOL-first-app/
├── src/
│   ├── app/
│   │   ├── home/              # Home-Komponente
│   │   ├── pages/             # Seiten-Komponenten
│   │   │   ├── oceans/        # Ozeane-Übersicht
│   │   │   ├── seas/          # Meere-Übersicht
│   │   │   ├── quiz/          # Quiz-Funktionalität
│   │   │   └── quiz-resolve/  # Quiz-Resolver
│   │   ├── text-bild/         # Text-Bild-Komponente
│   │   ├── tierarten/         # Tierarten-Komponente
│   │   ├── water/             # Wasser-Komponente
│   │   ├── models/            # Datenmodelle
│   │   ├── data-service.ts    # Zentraler Datenservice
│   │   ├── app.routes.ts      # Routing-Konfiguration
│   │   └── app.ts             # Haupt-App-Komponente
│   ├── assets/                # Statische Assets
│   ├── styles.css             # Globale Styles
│   └── index.html             # HTML-Template
├── public/                    # Öffentliche Dateien
└── angular.json               # Angular-Konfiguration
```

## 🎯 Verfügbare Routen

### Hauptnavigation
- `/home` - Startseite
- `/oceans` - Ozeane-Übersicht
- `/seas` - Meere-Übersicht

### Ozeane
Für jeden Ozean (pacific, atlantic, indic, arctic, antarctic):
- `/oceans/{ozean}` - Ozean-Details
- `/oceans/{ozean}/tierarten` - Tierarten-Übersicht
- `/oceans/{ozean}/tierarten/{tier}` - Spezifische Tierart
- `/oceans/{ozean}/tiefen` - Tiefeninformationen
- `/oceans/{ozean}/klima` - Klimainformationen

### Meere
Für jedes Meer (mittelmeer, baltic, blacksea, redsea, nordsee):
- `/seas/{meer}` - Meer-Details
- `/seas/{meer}/tierarten` - Tierarten-Übersicht
- `/seas/{meer}/tierarten/{tier}` - Spezifische Tierart
- `/seas/{meer}/tiefen` - Tiefeninformationen
- `/seas/{meer}/klima` - Klimainformationen

## 🔧 Code Scaffolding

Neue Komponente generieren:

```bash
ng generate component component-name
```

Weitere verfügbare Schematics anzeigen:

```bash
ng generate --help
```

## 📝 Code-Formatierung

Das Projekt verwendet Prettier mit folgender Konfiguration:
- Print Width: 100 Zeichen
- Single Quotes: aktiviert
- Angular Parser für HTML-Dateien

## 🌐 Browser-Unterstützung

Die Anwendung unterstützt moderne Browser. Spezifische Browser-Konfigurationen können in der `.browserslistrc` Datei angepasst werden.

## 📚 Weitere Ressourcen

- [Angular Dokumentation](https://angular.dev)
- [Angular CLI Referenz](https://angular.dev/tools/cli)
- [TypeScript Dokumentation](https://www.typescriptlang.org/)

## 📄 Lizenz

Dieses Projekt ist privat (siehe `package.json`).


