# Projekt Kacheln

## Willkommen am Institut

Ersteinmal willkommen am Institut und viel Spaß bei deiner ersten Aufgabe :-)

### Tooling

Es lohnt sich für dich für diese erste Aufgabe und den Rest deiner "Computing for Humanities" Zeit folgende Tools zu installieren, das sind mitterweile die Schweizer Taschenmesse der Softwareentwicklung:

* Git <https://git-scm.com/>
* Visual Studio Code <https://code.visualstudio.com/>
* Windows Terminal (falls du Windows benutzt, ansonsten Oh-My-Bash):  <https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=de-de&gl=DE>


## Git 

Um dieses Repo auf deinen Rechner zu "clonen" musst du in deinem Terminal folgenden Befehl in einem Ordner deiner Wahl ausführen:

```bash

git clone https://github.com/LIfBi-SWD/relaunch-projects.git

```

Danach entsteht in diesem Ordner ein Unterordner /relaunch-projects der ab diesem Zeitpunt versionskontrolliert ist. Jetzt kannst du nach belieben neue Dateien anlegen und bestehende verändern.

Willst du einen Stand versionieren, dann führst du folgende Befehle durch:

```bash
git add .
```

```bash
git commit -m "Nette Beschreibung was geändert wurde"
```

Willst du die Änderungen auch bei Github veröffentlichen, führst du folgende Befehle durch: 

```bash
git push
```

Alternativ hat auch das Visual Studio Code eine wirklich schöne und einfache Oberfläche dafür: <https://www.youtube.com/watch?v=**TDO2dQL1Qn8**>



## Aufgabe
Drei neue Ansichten für die Projektkacheln als Diskusionsgrundlage zu erstellen:

1. Nur Logo falls vorhanden
2. Logo und Name
3. Logo, "Acronym | Name"


Die Farbe der Beschriftung der Projekte sollte auf dunkelblau (in CSS `var(--lifbi-blue-dark)`) gewechselt werden: `#4242b1`.

Die Logos kannst du hier "klauen": <https://www.lifbi.de/#member_main>

### Links
* Styleguide: <https://app.zeplin.io/project/5ca6ff41139a447afe1a54b3/styleguide>
* Design Seitenübersichten: <https://app.zeplin.io/project/5ca6ff41139a447afe1a54b3/dashboard>
* Styleguide für unser CSS: <http://web-dev.neps-data.de/lifbirelaunch_sass/#cards>
* Bootstrap: <https://getbootstrap.com/docs/4.6/content/images/>