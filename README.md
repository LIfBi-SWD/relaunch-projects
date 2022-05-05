# Projekt Kacheln

## Willkommen am Institut

Ersteinmal willkommen am Institut und viel Spaß bei deiner ersten Aufgabe :-)

### Tooling

Es lohnt sich für dich für diese erste Aufgabe und den Rest deiner "Computing for Humanities" Zeit folgende Tools zu installieren, das sind mitterweile die Schweizer Taschenmesse der Softwareentwicklung:

* Git https://git-scm.com/
* Visual Studio Code https://code.visualstudio.com/
* Windows Terminal (falls du Windows benutzt, ansonsten Oh-My-Bash):  https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=de-de&gl=DE


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


## Aufgabe
Drei neue Ansichten bauen:

1. Nur Logo falls vorhanden
2. Logo und Name
3. Logo, "Acronym | Name"


Die Farbe der Beschriftung der Projekte sollte auf dunkelblau (in CSS `var(--lifbi-blue-dark)`) gewechselt werden: `#4242b1`.
