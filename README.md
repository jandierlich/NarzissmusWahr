# NarzissmusWahr

Eine kostenlose, werbefreie Aufklärungs-App zum Thema Narzissmus — für Erwachsene und Kinder. Reine Informations-App, **keine** medizinische Anwendung, keine Diagnosestellung.

## Inhalte
- **Grundlagen** — Was ist Narzissmus, Ursachen/Hintergründe, Formen, Persönlichkeitszug vs. Störung
- **Erwachsene** — Muster erkennen (Love Bombing, Gaslighting, DARVO, Triangulation, …), Beziehung/Job/Familie, Umgang im Alltag (Grey Rock, JADE, Grenzen), Trennung & Ausstieg, Selbstfürsorge
- **Kinder** — kindgerecht erklärt, Ratgeber für Eltern/Bezugspersonen, Co-Elternschaft
- **Lexikon** — rund 30 Fachbegriffe von A–Z mit Suche
- **Tipps** — Kommunikationsskripte, Grenzen setzen, Selbstschutz-Checkliste, Dokumentation
- **Hilfe** — kostenlose, anonyme deutsche Beratungsstellen & Notrufnummern, Quellenverzeichnis

## Technik
- Reines HTML/CSS/JavaScript (Vanilla), keine Frameworks, keine externen Bibliotheken
- Keine Google Fonts — ausschließlich Systemschriften
- Keine Cookies, kein Tracking, keine Analyse-Tools
- Speichert lokal nur die gewählte Anzeigeeinstellung (hell/dunkel) via `localStorage`
- Offline nutzbar dank Service Worker (`sw.js`)
- Installierbar als PWA auf iOS (Safari → Teilen → „Zum Home-Bildschirm") und Android (Chrome → Menü → „App installieren")

## Installation auf GitHub Pages
1. Neues (oder bestehendes) öffentliches GitHub-Repository anlegen.
2. **Alle** Dateien aus diesem Ordner direkt ins Repository-Root hochladen (keinen umschließenden Unterordner erzeugen):
   - `index.html`
   - `app.html`
   - `style.css`
   - `app.js`
   - `app.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `impressum.html`
   - `datenschutz.html`
   - `README.md`
3. Unter **Settings → Pages** als Quelle den Branch `main` (Ordner `/root`) auswählen.
4. Die App ist danach unter `https://<benutzername>.github.io/<repositoryname>/` erreichbar — das ist automatisch `index.html`, die Startseite.

## Lizenz / Rechtliches
Eigenständige Kreation ohne Drittanbieter-Bibliotheken, -Schriftarten oder -Icons — dadurch keine Lizenzabhängigkeiten. Fachliche Inhalte basieren auf allgemein zugänglicher, anerkannter Fachliteratur (siehe Bereich „Hilfe" → Quellen in der App). Impressum und Datenschutzerklärung sind bereits mit den hinterlegten Kontaktdaten befüllt.
