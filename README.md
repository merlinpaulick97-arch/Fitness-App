# Trainingsgewichte

Kleine Handy-App (PWA) für das Gerätetraining: zu jedem Gerät ein Bild, das aktuelle Trainingsgewicht und eine Statistik mit Verlaufskurve.

- 30 Geräte in 10 Muskelgruppen sind vorbelegt, weitere lassen sich hinzufügen.
- Jedes Gerät hat eine Zeichnung; ein eigenes Foto kann direkt mit der Handykamera aufgenommen werden.
- Pro Tag wird ein Gewicht gespeichert. Die Statistik zeigt Start, Aktuell, Bestwert, Veränderung und den Verlauf.
- Alle Daten bleiben im Browser des Geräts (`localStorage`). Über „Sicherung“ lassen sie sich als Text kopieren und wieder einspielen.

## Aufs Handy bringen

Die App besteht nur aus statischen Dateien, ohne Build-Schritt.

1. In GitHub unter **Settings → Pages** als Quelle „Deploy from a branch“ wählen (Branch mit diesen Dateien, Ordner `/`).
2. Die Pages-Adresse auf dem Handy öffnen.
3. Im Browser-Menü „Zum Startbildschirm hinzufügen“ wählen. Danach läuft die App auch ohne Netz.

Lokal testen: `python3 -m http.server` im Projektordner und `http://localhost:8000` öffnen.
