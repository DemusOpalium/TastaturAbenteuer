README / Projektübersicht

Schreibabenteuer DemusOpalium ist ein Open‑Source Schreibspiel, in dem du in variablen Zeitmodi (1–5 Minuten) spannende Schreib‑Challenges meisterst.
Folgende Hauptfunktionen bietet das Projekt:

    Mehrere Spielmodi:

        Freewrite: Kreatives Schreiben ohne Strafe

        Hardcore: Jeder Fehler oder Inaktivität löscht den Text

        Adventure: Kämpfe gegen einen „Wort Boss“

        Copy Challenge: Tippe vorgegebene Sätze exakt nach

        Kreativmodus: Mit Schreibimpuls

    Belohnungssystem & Erfolge:
    Erfolge werden freigeschaltet, wenn du bestimmte Meilensteine (z. B. eine bestimmte Wortanzahl) erreichst. Rewards wie „Schriftfarbe Blau freigeschaltet!“ oder Emoji-Rewards werden nur dann angezeigt, wenn du den entsprechenden Kauf im Shop tätigst.

    Shop & Inventar:
    Im Shop kannst du mit deinen Credits kosmetische Upgrades wie neue Profilbilder oder Cursor kaufen. Diese Änderungen dienen ausschließlich der Unterhaltung und haben keinen Einfluss auf die Kernmechanik des Spiels.

    Profil‑Sicherheit:
    Um zu verhindern, dass Credits manuell in der JSON-Datei manipuliert werden, wird beim Speichern des Profils zusätzlich eine einfache Checksumme (basierend auf den Credits plus einem geheimen Schlüssel) erzeugt und mitgespeichert. Beim Laden des Profils wird diese Checksumme neu berechnet und überprüft. Stimmen die Werte nicht überein, wird ein Betrugsversuch gemeldet.

    Open Source:
    Der gesamte Code ist offen einsehbar und soll der Community als Basis für weitere Verbesserungen dienen.

Hintergrund

Nach 17 Jahren intensiver Tipp-Erfahrung und dem Experimentieren mit meiner neuen HotSwap 60%-Tastatur – inklusive einer mit Kork gedämmten Unterlage – stellte sich die Frage: Wie schnell kann ich wirklich tippen? Auf der Suche nach einem passenden Tool stieß ich auf „Write or Die“, das jedoch nicht mehr aktiv weiterentwickelt wurde. Andere Lösungen erforderten oftmals eine aufwendige Registrierung – etwas, das mir nicht zusagte.
