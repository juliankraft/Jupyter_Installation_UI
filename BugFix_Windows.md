# Deine Situation

Du hast alles installiert wie in der Anleitung. Allerdings, wenn du den Befehl `jupyter lab` in der Konsole eingibst kommt der Fehler `jupyter: command not found`.

# Deine Lösung

## Python sauber deinstallieren und system bereinigen

Du musst Python und Python launcher wieder deinstallieren. Das geht so: 

1. Gehe zu den Windows-Systemeinstellungen, indem du auf das Windows-Symbol in der Taskleiste klicken und dann auf das Zahnrad-Symbol ("Einstellungen") klicken.

2. In den Systemeinstellungen wähle "Apps" oder "Programme" (abhängig von Ihrer Windows-Version).

3. Suchen Sie in der Liste der installierten Programme nach "Python". Es sollten mehrere Einträge für verschiedene Python-Versionen vorhanden sein. Wählen Sie eine Python-Version aus, die Sie deinstallieren möchten, und klicken Sie auf "Deinstallieren". Befolgen Sie die Deinstallationsanweisungen im Deinstallationsassistenten.

4. Wiederholen Sie diesen Schritt für alle installierten Python-Versionen und den Python launcher.

Das war der einfache Teil. Nun wird es ein wenig mühsam. Nun müssen noch die Überreste früherer Installationen bereinigt werden.

An folgenden Orten sollte alles was mit python zu tun hat gelöscht werden:

C:\Program Files\
C:\Users\<deinBenutzername>\AppData\Local\Programs\
C:\Users\<deinBenutzername>\AppData\Roaming\

Das heisst du musst in diesen Verzeichnissen die folgenden Verzeichnisse mit ihrem Inhalt löschen, sofern sie vorhanden sind.

python<br>
python311<br>
pip<br>

Nun gibt es eine Schwierigkeit. Der Ordner AppData wird für dich nicht sichtbar sein. Um diesen Ordner sichtbar zu machen, musst du wie folgt vorgehen:

Um versteckte Dateien im Windows Explorer sichtbar zu machen, folge diesen Schritten:

1. **Öffne den Windows Explorer**:
   - Drücke die `Win + E` Tastenkombination auf deiner Tastatur oder klicke auf das Windows-Symbol in der Taskleiste und wähle "Explorer" aus.

2. **Navigiere zu "Ansicht"**:
   - Oben im Windows Explorer-Fenster findest du eine Menüleiste. Wenn sie nicht sichtbar ist, drücke die `Alt`-Taste auf deiner Tastatur, um sie vorübergehend anzuzeigen.

3. **Öffne die "Optionen" oder "Ordner- und Suchoptionen"**:
   - Klicke auf "Ansicht" in der Menüleiste. Im Dropdown-Menü, das sich öffnet, wähle "Optionen" (in älteren Windows-Versionen kann es "Ordneroptionen" oder "Ordner- und Suchoptionen" heißen).

4. **Wechsle zum Register "Ansicht"**:
   - In den Ordneroptionen wechselst du zum Register "Ansicht" (oder "View" in englischen Windows-Versionen).

5. **Aktiviere die Option "Versteckte Dateien, Ordner und Laufwerke anzeigen"**:
   - Setze das Häkchen bei "Versteckte Dateien, Ordner und Laufwerke anzeigen".
Damit solltest du versteckte Dateien im Windows Explorer sichtbar machen können. Wenn du weitere Fragen hast, stehe ich gerne zur Verfügung.

Falls dich die vielen nutzlosen Ordner im Explorer stressen, kannst du die Einstellung nachher ja einfach wieder ändern.

## Erneute Installation von Python

zurück zur Anleitung für die Installation




