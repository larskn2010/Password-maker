Passwort-Manager 
Hier kannst du deine Passwörter sicher speichern und sie wieder anzeigen lassen 
jedes Verzeichnis kriegt sein eigenes geheimes Master-Passwort!

Was das Script kann
Passwörter zufällig erstellen

Account, Benutzername und Passwort speichern

Jedes Passwort-Datei-Ordner (= Datenbank) hat eigenes Passwort, das nur du kennst

Daten werden verschlüsselt mit Kryptografie

So geht’s
Installiere Python am besten von python.org, Version 3.8+

Kryptografie-Bibliothek installieren:
Gib das in die Konsole ein:

text
pip install cryptography
Script starten:
Kopiere main.py in einen eigenen Ordner.
Dann:

text
python main.py
Beim ersten Start:
Wähle einen Dateinamen, zum Beispiel geheim.dat.
Leg dein eigenes Master-Passwort fest und merk es dir unbedingt!

Einträge machen, Passwörter speichern – fertig!
Beim erneuten Start einfach Dateinamen eingeben und Passwort tippen.

Wie mach ich das als Desktop-App?
Du kannst das Skript als .py direkt auf den Desktop legen.

Wenn du eine richtige „App“ willst, hol dir PyInstaller:

text
pip install pyinstaller
pyinstaller --onefile main.py
Danach findest du in dist eine .exe – die kannst du ziehen wie jede App.

Was du wissen musst
Dein Master-Passwort ist das Wichtigste! Vergess es NIE!

Jede Passwortdatei (z.B. games.dat, schule.dat) kann ein anderes Passwort haben.

Die Passwörter werden nur verschlüsselt gespeichert. Niemand kommt ohne Masterpasswort rein.

Keine echten Cloud-Sachen, alles bleibt bei dir auf dem Computer.

Falls was nicht klappt…
Schreib mir ein GitHub-Issue, ich helf, wenn ich Zeit hab!

Prüfe, ob cryptography wirklich installiert ist.

Bei Fehlermeldung: Brauchst vermutlich Python mit „Tkinter“, falls du später ne GUI willst.
