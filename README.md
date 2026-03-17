# Personal Portfolio Website

Statische One-Page-Portfolio-Seite in reinem HTML, CSS und JavaScript. Das Design ist fuer GitHub Pages gedacht und funktioniert ohne Build-Schritt oder Backend.

## Dateien

- `index.html` enthaelt Struktur und Inhalte
- `styles.css` enthaelt das komplette Styling
- `script.js` enthaelt dezente Interaktionen

## Deployment mit GitHub Pages

1. Repository auf GitHub pushen.
2. In GitHub das Repository oeffnen.
3. `Settings` > `Pages` aufrufen.
4. Unter `Build and deployment` bei `Source` die Option `Deploy from a branch` waehlen.
5. Branch `main` und Ordner `/ (root)` auswaehlen.
6. Speichern. GitHub Pages veroeffentlicht die Seite danach automatisch.

Wenn das Repository kein User-/Org-Repository ist, liegt die URL spaeter in der Regel unter:

`https://<github-name>.github.io/<repository-name>/`

## Inhalte anpassen

Diese Stellen sind fuer persoenliche Anpassungen gedacht:

- Name:
  `index.html` im Hero (`<h1>`), im `<title>` und im Footer
- Intro-Text:
  `index.html` im Hero, in `#about` und in `#values`
- Profilbild:
  `index.html` im Hero-Bereich innerhalb von `.portrait-frame`
- Projekte:
  `index.html` im Abschnitt `#projects`
- Kontaktlinks:
  `index.html` im Abschnitt `#contact`

## Hinweise

- Nur relative lokale Dateien werden fuer CSS und JavaScript verwendet, daher ist die Seite direkt GitHub-Pages-tauglich.
- Das aktuelle Profilbild ist ein Platzhalter und sollte vor dem produktiven Einsatz ersetzt werden.
- Die Seite verwendet keine Frameworks, keinen Build-Prozess und keine externen Bibliotheken.
- Fuer ein echtes Profilbild kann der Platzhalter in `.portrait-frame` durch ein lokales `<img src="assets/profile.jpg" alt="...">` ersetzt werden.
- Falls du lokale Bilder hinzufuegst, lege sie am besten in einen Ordner wie `assets/` und verwende relative Pfade, z. B. `assets/profile.jpg`.
