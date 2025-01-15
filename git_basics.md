# Markdown und Git

## Schritte
Es wird hier dokumentiert, welche Schritte in dem Repository genau vergnommen werden. 

### Schritt 1
Eröffnung vom öffentlichen Repository IN250_HunzikerPatricia_Docs auf GitHub. 

### Schritt 2
1. Visual Studio Code wurde gestartet.
2. Über die Tastenkombination **STRG + Umschalt + P** wurde der Befehl **git:Clone** aufgerufen. 
3. Danach habe ich den GitHub-Link eingegeben: [https://github.com/TizznS/IN250_HunzikerPatricia_Docs-.git]
4. Das Repository wurde anschliessend lokal in meinem gewünschten Ordner gespeichert.

### Schritt 3
1. Markdown Cheatsheet, was im vorherigen Unterricht angelegt wurde, in den gleichen Ordner wie das Repository verschoben. 
2. CMD geöffnet und auf den Ordner navigiert, wo das Repository angelegt wurde. 
3. "Dir" verwendet um zu prüfen, ob ich im richtigen Ordner bin und mir das Repository und die Markdown Datei angezeigt wird. 
4. Mit dem Befehl copy markdown.md "C:\Users\dice9\OneDrive\Desktop\DevEn\IN250_HunzikerPatricia_Docs- in das Repository kopiert. 
5. git add markdown.md ausgeführt um es zum Repository hinzuzufügen. 
6. git commit -m "Initial commit" in der Konsole ausgeführt, um einen Commit zu erstellen mit der Message "Initial commit"
7. git log zum prüfen, ob der Commit erfolgreich war. 

### Schritt 4

1. Visual Studio Code wurde geöffnet.
2. Neues File anelegt unter meinen Repository mit dem namen "gitignore".
3. *.log und geheimeBankinformationen.txt ergänzt. 
4. Via Visual Studio Code Commited mit der Nachricht “Add gitignore".


### Schritt 5
1. In der Konsole via mkdir einen neuen Ordner angelegt. 
2. Anschliessend via Konsole auf den Ordner navigiert. 
3. via Git Init ein lokales Repository angelegt. 
4. Folgenden Befehl eingegeben git remote add origin https://github.com/TizznS/IN250_HunzikerPatricia_Docs-.git
5. Befehl git pull origin main eingegeben, aber eine Fehlermeldung erhalten "fatal: couldn't find remote ref main"
6. Im Repository über Visual Studio Code eine main Datei angelegt. 
7. Committed aber main befindet sich nicht im GitHub
8. via git remote -v geprüft ob Verbindung besteht und anschliessend git push -u origin main verwendet um auf Github zu pushen. 
9. wieder im lokalen Ordner das andere Repository geöffnet und git pull origin main durchgeführt. Nun sind Daten vorhanden. 
10.Ich habe im anderen lokalen Repository eine änderung vorgenommen, und es hat auf Githubs synchronisiert. Ich musste aber beim ursprünglichen Repository wieder git pull machen um die änderungen zu erhalten. 

#### Erkenntnis
Existieren mehrere lokale Repositories müssen mit git pull und git push synchronisiert werden, um Änderungen mit dem Remote-Repository synchron zu halten.
Der Button Synchronisieren im Visual Studio Code macht git pull & git push gleichzeitig. Ein Commit ist nur lokal gespeichert. Erst durch Push ist er auf Github. 

## Aufgabe 6 Markdown & Git


### Warum Git?
Git ermöglicht Versionskontrolle, Zusammenarbeit und Rückverfolgbarkeit von Änderungen, was die Entwicklung effizienter und sicherer macht.

### Warum Commit und Push vor der Flucht?
Damit der aktuelle Stand der Arbeit gesichert und für das Team verfügbar ist – selbst bei einem Feuer. Daten retten, dann sich selbst!