# lib/ – lokale Skripte für <model-viewer>

Lege hier zwei Dateien ab (direkt aus dem CDN heruntergeladen), damit die Seite ohne externes CDN läuft:

1. model-viewer.min.js
2. model-viewer-legacy.js

Offizielle Quellen (wähle eine, Rechtsklick → Speichern unter):

- jsDelivr Paketübersicht (@google/model-viewer):
  https://www.jsdelivr.com/package/npm/@google/model-viewer
  Beispiel (Version fixiert, empfohlen):
  https://cdn.jsdelivr.net/npm/@google/model-viewer@4.0.0/dist/model-viewer.min.js
  https://cdn.jsdelivr.net/npm/@google/model-viewer@4.0.0/dist/model-viewer-legacy.js

- unpkg Verzeichnis:
  https://www.unpkg.com/@google/model-viewer/dist/
  Beispiel (neueste Version – kann sich ändern):
  https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js
  https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js

Nachdem beide Dateien hier liegen, sollte die Seite unter GitHub Pages sofort funktionieren.
