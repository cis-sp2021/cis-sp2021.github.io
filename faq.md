**Häufig gestellte Fragen und Hinweise(Q&A)**

- *Wie laufen die Übungen ab?* <br>
Es wird eine Zentralübung stattfinden, in welcher die Lösungen zu den Programmieraufgaben präsentiert werden.
Zusätzlich bieten wir ein Tutorium an, welches freitags von 10 bis 12 Uhr stattfindet.
Dort werden alle Fragen, welche in dieser Woche gestellt wurden, besprochen.

- *Wird es dieses Semester noch Präsenzveranstaltungen geben?* <br>
Dieser Kurs findet dieses Semester ausschließlich online statt.

- *An wen wende ich mich, wenn ich Frage habe?* <br>
Sie können den Dozenten und die Tutoren unter der E-Mail Adresse sp2021@cis.lmu.de erreichen.

- *Ich kenne die anderen Mitglieder meiner Gruppe nicht, wie kann ich mich mit ihnen Kontakt aufnehmen, um gemeinsam die Programmieraufgaben zu lösen?* <br>
Idealerweise nutzen Sie die Gitlab-Issues dafür. Hier eine kurze Anleitung zu Gitlab [Issues](https://docs.gitlab.com/ee/user/project/issues/).

- *Wie verbinde ich mein Gitlab-Projekt mit Pycharm?* <br>
Sie können das Gitlab Projekt entweder mit SSH-Schlüssel oder mit HTTPS auf Ihren PC klonen. <br>
1). Gitlab -> Project -> Clone -> Clone with SSH/HTTPS (Wie man einen SSH-Schüssel anlegen kann, können Sie in der nächsten Frage lesen) <br>
2). Pycharm -> VCS -> Get from Version Control -> den kopierten Link eingeben -> add file to Git -> Ja <br>

- *Wie kann ich einen ssh Schlüssel zu meinem Profil hinzufügen?* <br>
Mit SSH-Schlüsseln können Sie eine sichere Verbindung zwischen Ihrem Computer und GitLab herstellen. Unter [diesem Link](https://gitlab2.cip.ifi.lmu.de/profile/keys) können Sie einen ssh Schlüssel für Ihren gitlab Account anlegen. Wie man einen ssh Schlüssel erstellen kann [sehen Sie hier](https://gitlab2.cip.ifi.lmu.de/help/ssh/README#generating-a-new-ssh-key-pair).

- *Ich kann leider eine Bibliothek in Python wie z.B. nltk nicht installieren, was soll ich machen?* <br>
a. Falls Sie Pycharm nutzen, versuchen Sie es bitte hier zu installieren: <br>
Settings/Preferences  → Project: → Project Interpreter → + → nltk eingeben → install package → done <br>
b. Falls Sie kein Pycharm nutzen, können Sie diesen Befehl im Terminal ausführen:
pip3 install --user nltk <br>
Falls es dann immernoch nicht klappt, wenden Sie sich bitte an die Tutoren oder geben Sie die Fehlermeldung in einer Suchmaschine ein.<br>
PS: Es wird empfohlen die Entwicklungsumgebung PyCharm für die Bearbeitung der Programmieraufgaben zu nutzen. Diese unterstützt insbesondere auch eine grafische Oberfläche und Integration für Git. Eine kurze Einleitung zu PyCharm finden Sie [hier](pycharm.pdf).<br>

- *Ich kann die Unit Tests nicht ausführen, woran könnte es liegen?* <br>
Ein häufiger Fehler ist, dass die Unit Tests nicht im src Ordner ausgeführt werden. Nachdem Sie sichergestellt haben, dass Sie sich im src Ornder befinden, sollten Sie den folgenden Befehl im Terminal ausführen können: <br>
Beispiel:  python3 -m unittest -v hw03_documents/test_documents.py
Falls es trotzdem nicht funktioniert und sie PyCharm benutzen, stellen Sie bitte sicher, dass der src Ordner als “sources root” markiert wurde. <br>
Rechtsklick auf src → mark directory as → sources root. <br>

- *Wie wird die Übungs- und Vorlesungsklausur durchgeführt?* <br/>
  1. Zum Prüfungsbeginn wird Ihnen die Klausurangabe vom Dozenten an Ihre _@campus.lmu.de_ E-Mailadresse geschickt.
  2. Bearbeiten Sie die Klausur indem Sie:
     - die Klausur ausdrucken und die Aufgaben direkt auf dem Ausdruck handschriftlich bearbeiten,
     - die Aufgaben auf einem separaten Blatt handschriftlich bearbeiten,
     - oder die Aufgaben in einer digitalen Text-Datei berabeiten (vergessen Sie nicht zwischenzuspeichern).
  3. Stellen Sie sicher, dass sich Ihre Bearbeitungen klar den Aufgaben zuordnen lassen.
  4. Nach Ablauf der Prüfungszeit (jeweils 45 Minuten für die Vorlesungs- und Übungsklausur), 
     müssen Sie entweder Ihr handschriftliches Dokument einscannen und an die E-Mailadresse des Dozenten schicken 
     oder Ihre bearbeitetete Textdatei an die E-Mailadresse des Dozenten schicken
  5. Falls Ihre Email 10 Minuten nach Ablauf der Prüfungszeit nicht beim Dozenten angekommen ist, gilt die Klausur als nicht bearbeitet.
  6. Es gibt verschiedenen Programme (auch für Android, Linux, usw.), die Dokumenten einscannen und in ein PDF umzuwandeln können. 
     Stellen Sie sicher, dass Sie über ein geeignetes Programm verfügen (und üben Sie dessen Anwendung).

