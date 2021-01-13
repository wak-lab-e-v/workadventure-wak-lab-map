# WorkAdventure Map Starter Kit

Dies ist ein Starter-Kit, mit dem Sie Ihre eigene Karte f�r 
[WorkAdventure](https://workadventu.re) erstellen k�nnen.

## Werkzeuge, die Sie ben�tigen

Um Ihre eigene Karte f�r WorkAdventure zu erstellen, ben�tigen Sie:

- die Software [Tiled Editor] (https://www.mapeditor.org/)
- "Kacheln" (d. h. Bilder) zum Erstellen Ihrer Karte (dieses Starter-Kit bietet ein gutes Standard-Kachelset f�r B�ros)
- ein Webserver zur Bereitstellung Ihrer Karte (in diesem Starter-Kit wird vorgeschlagen, statische Github-Seiten als kostenlosen und leistungsf�higen Webserver zu verwenden).

## Anfangen

Auf der [Github-Repository-Seite] (https://github.com/thecodingmachine/workadventure-map-starter-kit),
Klicken Sie auf die Schaltfl�che ** "Diese Vorlage verwenden" **. Sie werden aufgefordert, einen Repository-Namen f�r Ihre Karte einzugeben.

![](docs/create_repo.png)

Stellen Sie sicher, dass das Repository "�ffentlich" ist.

Klicken Sie in Ihrem neu erstellten Repository auf die Registerkarte ** Einstellungen ** und scrollen Sie zum Abschnitt ** GitHub-Seiten **.
W�hlen Sie dann den Zweig ** gh-pages ** aus.

![](docs/github_pages.png)

Warten Sie einige Minuten, bis ein Github eine neue Website mit dem Inhalt des Repositorys bereitstellt.
Die Adresse der Website ist im Bereich "GitHub-Seiten" sichtbar.

![](docs/website_address.png)

Klick auf den Link. Sie sollten direkt zu WorkAdventure auf Ihrer Karte weitergeleitet werden!

## Anpassen Ihrer Karte

Ihre Karte ist jetzt online. Sie m�ssen es anpassen.

### Klonen der Karte

Beginnen Sie mit dem Klonen der Karte. Wenn Sie an Git und GitHub gew�hnt sind, klonen Sie einfach die Karte
mit Ihrem bevorzugten Werkzeug auf Ihren Computer und [zum n�chsten Kapitel springen] (# Laden der Karte in Kacheln).

Wenn Sie Git noch nicht kennen, bedeutet das Klonen der Karte, dass Sie die Karte auf Ihren Computer herunterladen.
Dazu ben�tigen Sie Git oder ein Git-kompatibles Tool. Unser Rat ist zu verwenden
[GitHub Desktop](https://desktop.github.com/).

TODO: testen und fortfahren

### Laden der Karte in Tiled

Die Beispielkarte befindet sich in der Datei "map.json".
Sie k�nnen diese Datei in [Kacheln] (https://www.mapeditor.org/) laden.

Jetzt liegt es an Ihnen, die Karte zu bearbeiten und Ihre eigene Karte zu schreiben.

Einige Ressourcen zu Tiled:

- [Gekachelte Dokumentation] (https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled Video Tutorials] (https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### �ber WorkAdventu.re-Karten

Um eine Karte zu entwerfen, die von WorkAdventure gelesen werden kann, m�ssen Sie einige Einschr�nkungen beachten.

Insbesondere m�ssen Sie:

- Legen Sie eine Startposition f�r die Spieler fest
- Konfigurieren Sie die "Bodenebene" (damit WorkAdventure Zeichen �ber dem Boden, aber unter der Decke korrekt anzeigen kann).
- Schlie�lich k�nnen Sie Ausg�nge platzieren, die auf andere Karten verweisen

All dies wird in der [WorkAdventure-Dokumentation] (https://github.com/thecodingmachine/workadventure/#designing-a-map) beschrieben.
Bitte probieren Sie es unbedingt aus.

### Karte verschieben

Wenn Ihre �nderungen fertig sind, m�ssen Sie die �nderungen "festschreiben" und "zur�ckschieben" an GitHub.
Warten Sie einfach ein paar Minuten, und Ihre Karte wird automatisch an den Webserver der GitHub-Seiten weitergegeben.


### Karte hochladen
git add .
git commit -m "Meine neue Karte"
git push

TODO:
Mehr zu diesem Ausgangstext
F�r weitere �bersetzungsinformationen ist ein Ausgangstext erforderlich
Feedback geben
Seitenleisten
