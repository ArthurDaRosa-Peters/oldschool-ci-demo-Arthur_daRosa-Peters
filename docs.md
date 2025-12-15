    1. Was macht das Dockerfile?
Der Dockerfile erzeugt ein Dockerimage das eine Minimalen Alpine Umgebung besitzt, kopiert anschließend unser app.sh Skript ins Workdir und setzt         ausführrechte für das Skript und setzt zuletzt den startbefehl für den Container auf /app.sh

    2. Was ist der Zweck der Pipeline?
CI/CD, also nach jedem Push den gepushten Code hochzuladen und zu testen und anschließend zu veröffentlichen

    3. Was war für dich der schwierigste Teil dieser Aufgabe und warum?
Der build-Command und die Rechtschreibung, weil ich den "." als Argument für den build-Command vergessen habe und zwischendurch mehrere Tippfehler in dem Ausgabecheck hatte
