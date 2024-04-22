Aufgabe 1: Git Repository initialisieren
Ich habe einen neuen Ordner unter F:\GIT-Local angelegt.
Im VSC-Terminal bin ich zu diesem Ordner navigiert.
Mit "git init" habe ich es als neues Git-Repository intitialisiert.
Aufgabe 2: Einfaches Python-Skript erstellen und commiten
Im neuen Git-Repository GIT-Local habe ich eine Pyton-Datei mit Namen "hello.py" angelegt und in diese die Zeile "print("Hallo Welt")" eingefügt und die Datei gespeichert.
Danach habe ich sie mit "git add hello.py" zum Repository hinzugefügt und mit "git commit -m "Hello.py hinzugefügt" commitet.
Nun habe ich eine Branch für die Funktionserweiterung hinzugefügt mit dem Befehl "git checkout -b neue-funktion"
Danach habe ich in die hello.py um die neue Funktion nach dem Nutzernamen zu fragen und eine personalisierte Empfehlung auszugeben erweitert und die Datei gespeichert und mit "git ass -A" der Branch "neue-funktion" hinzugefügt und mit "git commit -m "personalisierte Begrüßung hinzugefügt." commitet.
Dann bin ich mit "git checkout main" zur Main-Branch zurückgewechselt und habe mit "git merge neuen-funktion" die neue Funktion in die Main-Branch gemerged/integriert. Danach habe ich diese README.md geschrieben und gespeichert, die ich dann mit "git add README.md" dem Repository hinzugefügt habe, danach mit "git commit -m "Dokumentation hinzugefügt" commitet und mit "git push -u origin main" auf die Main-Branch zu mergen.