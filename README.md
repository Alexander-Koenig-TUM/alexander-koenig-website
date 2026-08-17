# alexander-koenig.eu

Personal website for Prof. Dr. Alexander König.

## Deployment

This site is hosted via GitHub Pages. Any push to the `main` branch automatically deploys.

## Setup (einmalig)

1. Erstelle ein neues GitHub Repository (z.B. `alexander-koenig-website`)
2. Pushe den Inhalt dieses Ordners in das Repository
3. Gehe zu Repository > Settings > Pages > Source: "Deploy from a branch" > Branch: `main` > Ordner: `/ (root)`
4. Bei Deinem Domain-Registrar: Setze einen CNAME-Eintrag für `alexander-koenig.eu` auf `DEIN_GITHUB_USERNAME.github.io`
5. Warte ca. 10-30 Minuten, bis DNS propagiert hat
6. Aktiviere "Enforce HTTPS" in den GitHub Pages Settings

## Dateien

- `index.html` — deutsche Hauptseite
- `english.html` — englische Hauptseite
- `ueber-mich.html` / `about-en.html` — Profil auf Deutsch und Englisch
- `impressum.html` / `impressum-en.html` — Impressum auf Deutsch und Englisch
- `datenschutz.html` / `privacy.html` — Datenschutz auf Deutsch und Englisch
- `CNAME` — Custom-Domain-Konfiguration
- `images/` — lokal eingebundene Bilder und Social Preview

## Änderungen vornehmen

Bearbeite die HTML-Dateien direkt und pushe zu GitHub. Die Seite aktualisiert sich automatisch innerhalb von 1-2 Minuten.
