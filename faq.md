**Häufig gestellte Fragen und Hinweise(Q&A)**

- *Wie laufen die Übungen ab?* <br>
Es wird eine Zentralübung stattfinden, in welcher die Lösungen zu den Programmieraufgaben präsentiert werden.
Zusätzlich bieten wir ein Tutorium an, welches freitags von 10 bis 12 Uhr stattfindet.
Dort werden alle Fragen, welche in dieser Woche gestellt wurden, besprochen.

- *Wird es dieses Semester noch Präsenzveranstaltungen geben?* <br>
Dieser Kurs findet dieses Semester ausschließlich online statt.

- *An wen wende ich mich, wenn ich Frage habe?* <br>
Sie können den Dozenten und die Tutoren unter der E-Mail Adresse sp2021@cis.lmu.de erreichen.

- *Wie verbinde ich meinen Gitlab-Projekt mit Pycharm?* <br>
Sie könnnen entweder mit SSH-Schlüssel oder mit HTTPS den Gitlab Projekt in Ihren PC klonen. <br>
1). Gitlab -> Projekt -> Clone -> Clone with SSH/HTTPS (Wie man SSH-Schüssel anlegen soll, lesen Sie bitte die nächste Frage) <br>
2). Pycharm -> VCS -> Get from Version Control -> das kopierte Link eingeben -> add file to Git -> Ja <br>

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



