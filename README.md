# DokuPfad Homepage

Marketing-/Landingpage für [dokupfad.de](https://dokupfad.de), getrennt von der eigentlichen App (siehe [emologik-app](https://github.com/SKemologik/emologik-app)).

## Dateien

- `index.html` – die vollständige Landingpage (ein einziges, in sich geschlossenes HTML-Dokument: CSS und Schriften sind eingebettet, keine externen Abhängigkeiten)
- `favicon.svg` – Emologik-"E"-Icon, freigestellt, für moderne Browser
- `apple-touch-icon.png` – 180×180 PNG-Fallback fürs iPhone-Homescreen-Icon (Safari unterstützt SVG-Icons nicht zuverlässig)

## Deployment (IONOS)

`index.html`, `favicon.svg` und `apple-touch-icon.png` einfach in das Webspace-Root-Verzeichnis der Domain hochladen. Kein Build-Schritt, kein Server-Framework nötig – reines statisches HTML.

## Offene Punkte

- "Zur App"-Button verlinkt noch auf `#` – braucht die echte Login-URL der App
- Impressum: Registereintrag folgt bei Eintragung ins Handelsregister
