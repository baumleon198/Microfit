# MICROFIT 0.2 – iPhone-Web-App

## Inhalt
- `index.html`: App mit Trainingsauswahl, Countdown, Pausen, Varianten und Trainingsabschluss
- `manifest.webmanifest`: PWA-Metadaten
- `sw.js`: Offline-Caching
- `icon-192.png` und `icon-512.png`: App-Icons

## Auf dem iPhone 17 installieren
Eine PWA benötigt eine sichere HTTPS-Adresse (oder localhost). Eine ZIP-Datei direkt in Safari zu öffnen reicht für die Installation nicht.

1. Lade diesen Ordner auf einen statischen HTTPS-Host, z. B. GitHub Pages oder einen anderen Webhosting-Dienst.
2. Öffne die veröffentlichte Adresse in Safari auf dem iPhone.
3. Tippe auf „Teilen“ → „Zum Home-Bildschirm“ → „Hinzufügen“.
4. Starte MICROFIT über das neue Home-Bildschirm-Symbol.

## Hinweis zum Prototyp
Der Timer läuft sekundengenau im geöffneten App-Fenster. iOS kann Hintergrund-Tabs und gesperrte Bildschirme anhalten; deshalb ist dies noch kein zuverlässiger Hintergrund-Workout-Timer. Trainingsdaten werden lokal auf diesem Gerät im Browser gespeichert. Es gibt noch keine Cloud-Synchronisierung.

Die Trainingsvorschläge sind einfache Beispielprogramme und keine medizinische oder individuelle Trainingsberatung. Bei Schmerzen abbrechen und Übungen an Beweglichkeit und Leistungsstand anpassen. Mit „*“ markierte Varianten sind anspruchsvoller und für Einsteiger nicht als Standard gedacht.
