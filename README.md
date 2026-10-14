# phil.psue.de

Persönliche Website von Philipp Süß, Marketing Lead in Berlin.
Live unter [phil.psue.de](https://phil.psue.de/) (GitHub Pages, Custom Domain über `CNAME`).

## Aufbau

- Eine einzige `index.html`, ohne Build-Schritt und ohne Framework
- Schriften: Zilla Slab und Public Sans über Google Fonts
- Zweisprachig: Deutsch steht im HTML, Englisch im Wörterbuch `EN` im Skript am Ende der Datei.
  Jedes übersetzte Element trägt ein `data-i18n`-Attribut mit seinem Schlüssel.
- Sprache: `?lang=en` bzw. `?lang=de`, sonst die zuletzt gewählte, sonst die Browsersprache

## Inhalte ändern

1. Deutschen Text direkt in `index.html` ändern
2. Den passenden englischen Text unter demselben Schlüssel im `EN`-Objekt anpassen
3. Lokal ansehen: `python3 -m http.server` im Ordner starten und `http://localhost:8000` öffnen
