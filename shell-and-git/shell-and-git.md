# Git und Git Branches

## Standard workflow

Erst Lokal auf Git erstellen dann auf github hochladen

`git init` &rarr; Repository erstellen / initialisieren

`rm -rf .git` &rarr; Git Repository wird entfernt / Ordner wird wieder normaler Ordner

`git add <file-name.ending>` &rarr; Datei wird gestaged

`git add .` &rarr; alle Dateien werden gestaged, wir wählen aus was in unserem nächsten Commit drin sein soll

`git commit -m "<Message>"` &rarr; Alle staged Dateien werden comitted, Message auf englisch, im präsens,mit verb anfangen

`git push -u origin main` &rarr; Push all commits to repository auf Main Branch (-u = upstream // macht man beim ersten Mal)

`git remote add origin <SSH-Key>` &rarr; Verknüpfung zu Github-Repository mit entsprechendem SSH-Key herstellen

## Mehr wichtige Befehle

`git log` &rarr; commit Hostorie

`git log --oneline`&rarr; Historie untereinander anzeigen

`git remote -v` &rarr; Verknüpfung wird angezeigt
