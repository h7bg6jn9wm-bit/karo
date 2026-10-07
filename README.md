# SHK Theorie Trainer – V5 Fix

Drei Hauptbereiche:
1. Prüfungsmodus
2. Fragebögen zum Lernen
3. Diagnose

Die Diagnose ist jetzt Bestandteil derselben App-Struktur. Die Diagnose besitzt keinen eigenen Manifest-/Service-Worker mehr und kann dadurch nicht mehr versehentlich als Startseite der installierten App geöffnet werden. Der Zurück-Button führt zuverlässig zum Hauptmenü.

Für iPhone: Root-`index.html` über GitHub Pages öffnen und über Safari „Zum Home-Bildschirm“ hinzufügen.
