# Trainingsgewichte

Kleine Handy-App (PWA) für das Gerätetraining: zu jedem Gerät ein Bild, das aktuelle Trainingsgewicht und eine Statistik mit Verlaufskurve.

- 30 Geräte in 10 Muskelgruppen sind vorbelegt, weitere lassen sich hinzufügen.
- Jedes Gerät hat eine Zeichnung; ein eigenes Foto kann direkt mit der Handykamera aufgenommen werden.
- Pro Tag werden bis zu drei Sätze mit Gewicht gespeichert; ein Kalender zeigt, wann welche Übung gemacht wurde. Die Statistik zeigt Start, Aktuell, Bestwert, Veränderung und den Verlauf.
- Zu jedem vorbelegten Gerät gibt es kurze Tipps: Einstellen, Ausführen, Darauf achten.
- Alle Daten bleiben im Browser des Geräts (`localStorage`). Über „Sicherung“ lassen sie sich als Text kopieren und wieder einspielen.

## Aufs Handy bringen

Die App besteht nur aus statischen Dateien, ohne Build-Schritt.

1. In GitHub unter **Settings → Pages** als Quelle „Deploy from a branch“ wählen (Branch mit diesen Dateien, Ordner `/`).
2. Die Pages-Adresse auf dem Handy öffnen.
3. Im Browser-Menü „Zum Startbildschirm hinzufügen“ wählen. Danach läuft die App auch ohne Netz.

Lokal testen: `python3 -m http.server` im Projektordner und `http://localhost:8000` öffnen.

## Quellen der Gerätetipps

Die Tipps sind allgemeine Hinweise, zusammengefasst unter anderem aus:

- https://www.basic-fit.com/de-de/blog/fitness-machines-101
- https://www.fitbook.de/fitness/leg-extension
- https://www.fitbook.de/fitness/butterflymaschine-brusttraining
- https://www.fitbook.de/fitness/klimmzug-maschine-ausfuehrung
- https://www.fitbook.de/fitness/flys-am-kabelzug-ausfuehrung
- https://www.bulk.com/de/the-core-de/die-richtige-ausfuehrung-des-latzugs-auf-die-brust/
- https://www.dr-gumpert.de/html/beinstrecker.html
- https://www.wikifit.de/fitnessuebungen/beinmuskeltraining/beinpresse
- https://fitwill.app/de/exercise/2246/lever-seated-row/
- https://www.soletreadmills.com/blogs/news/how-to-do-hack-squat-proper-form-quads-glutes
- https://thatfitfriend.com/pendulum-squat-guide/
- https://www.yourhousefitness.com/blog/common-hip-thrust-mistakes
- https://csun.edu/src/accessibility/bgm
- https://www.uni-regensburg.de/fileadmin/user_upload/universitaet/einrichtungen/Sportzentrum/PDF/URAlive/Smith_Maschine.pdf
