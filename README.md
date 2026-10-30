# Trip Assistant

Persönlicher Reise-Assistent fürs iPhone, als Web-App (PWA): Eckdaten der Reise eingeben, dann gibt es Plan, Packliste und Tools wie Wetter, Wechselkurs und Sprachführer. Die Daten bleiben auf dem Gerät.

**App:** https://trolloberg.github.io/trip-assistant/

## Aufs iPhone holen
1. Den Link in Safari öffnen.
2. Teilen → „Zum Home-Bildschirm“.
3. Einmal mit Internet starten, danach läuft die App auch offline. Wetter und Kurse brauchen Internet.

Umzug von der alten Adresse (`london-navigator/travel/`): In der alten App „Backup exportieren“, in der neuen „Backup importieren“.

## Dateien
| Datei | Inhalt |
|---|---|
| `index.html` | die ganze App, HTML, CSS und JavaScript in einer Datei |
| `sw.js` | Offline-Cache. Bei jedem Update `VERSION` hochzählen |
| `manifest.webmanifest`, `icon-*.png` | Name und Icons für den Home-Bildschirm |

Kein Build, keine Abhängigkeiten. GitHub Pages veröffentlicht den Branch `gh-pages` direkt.
