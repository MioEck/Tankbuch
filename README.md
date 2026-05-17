# Tankbuch – Toyota Auris Hybrid

PWA zur Verwaltung des Kraftstoffverbrauchs.

## Deployment auf GitHub Pages

1. Neues Repository erstellen (z.B. `tankbuch`)
2. Diese Dateien hochladen:
   - `index.html` (← umbenennen von `tankbuch.html`)
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. In den Repository-Einstellungen unter **Pages** → Branch `main` → Ordner `/root`
4. App ist erreichbar unter `https://DEINNAME.github.io/tankbuch`

## Features

- CSV-Import (bestehende Numbers-Datei)
- Neue Tankungen erfassen
- Verbrauch nur bei Volltankung berechnet
- Temperatur automatisch per GPS + Open-Meteo
- Offline-fähig (Service Worker)
- Installierbar als App (PWA)
- CSV-Export
