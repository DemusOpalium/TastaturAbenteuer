Schreibabenteuer DemusOpalium

Schreibabenteuer DemusOpalium ist ein Open‑Source-Schreibspiel, in dem du in variablen Zeitmodi (1–5 Minuten) spannende Schreib‑Challenges meisterst – sei es kreativ, präzise oder unter hohem Druck! Das Spiel richtet sich vor allem an PC-Nutzer mit Tastatur, bietet aber auch eine voll responsive Version für mobile Geräte.
Hauptfunktionen und Spielmodi

    Mehrere Spielmodi:

        Freewrite: Kreatives Schreiben ohne Strafe.

        Hardcore: Jeder Fehler oder jede Inaktivität löscht den Text.

        Adventure: Stelle dich dem „Wort Boss“ und kämpfe mit deinen geschriebenen Wörtern.

        Copy Challenge: Tippe vorgegebene Sätze exakt nach – dank verbesserter Logik startet das Spiel per Enter-Taste zuverlässig, und beim Reset werden stets neue Sätze generiert.

        Kreativmodus: Mit inspirierenden Schreibimpulsen für deine Kreativität.

    Belohnungssystem & Erfolge:

        Schalte Erfolge frei, wenn du bestimmte Meilensteine (z. B. eine bestimmte Wortanzahl) erreichst.

        Erhalte Rewards und Abzeichen (wie spezielle Emoji-Rewards, Schriftfarben, etc.), die im Shop erworben werden können.

    Shop & Inventar:

        Kaufe kosmetische Upgrades wie neue Profilbilder, Glücksbringer und weitere Icons mit deinen verdienten Wissenspunkten.

        Das System wurde hinsichtlich der Anzeige und Bedienbarkeit verbessert – sowohl für PC als auch mobile Geräte wurden Icons und Buttons optimiert.

    Profil‑Sicherheit:

        Um Manipulationen (z. B. durch direktes Ändern der JSON-Datei) zu verhindern, wird beim Speichern des Profils eine einfache Checksumme (basierend auf den Wissenspunkten plus einem geheimen Schlüssel) erzeugt und mitgespeichert.

        Beim Laden des Profils wird diese Checksumme überprüft – bei Unstimmigkeiten wird ein möglicher Betrugsversuch gemeldet.

        Wichtig: Wir haben den Checksumme-Mechanismus erweitert, sodass jetzt auch alle relevanten Werte (wie dein Inventar an Glücksbringern) berücksichtigt werden.

    Copy Challenge Optimierungen:

        Verbesserte Logik bei den Copy Messages: Das Spiel startet nun zuverlässig per Enter-Taste, wenn der Start-Hinweis im Texteingabefeld angezeigt wird.

        Das Reset-Problem im Copy-Modus wurde behoben – es werden stets neue Sätze generiert.

Neue Features und Erweiterungen

    Namensänderung im Profil:
    Bisher gab es keine Möglichkeit, den Profilnamen zu ändern. Jetzt haben wir ein Eingabefeld und einen Button integriert, mit dem du deinen Namen direkt im Spiel anpassen kannst – die Änderung wird sofort in deinem Profilbereich angezeigt.

    Terminologie-Anpassungen:

        Credits wurden in Wissenspunkte umbenannt.

        Cursoren wurden durch Glücksbringer ersetzt – inklusive Anpassung aller zugehörigen Variablen, Shop-Items und Anzeigeelemente.

    Neue Kategorie "Code/Python":
    Wir haben eine spannende neue Kategorie eingeführt, die eine große Sammlung von Python-Code-Beispielen enthält:

        Easy (25 Beispiele): Basisbefehle, Variablenzuweisungen, Schleifen und einfache Ausgaben.

        Normal (15 Beispiele): Funktionen, Bedingungen, List Comprehensions, Dateioperationen und Klassen.

        Hard (10 Beispiele): Anspruchsvolle Beispiele wie Merge-Sort, DataFrame-Operationen, Dekoratoren, Singleton-Pattern, asynchrone Programmierung und Generatoren – humorvoll und übersichtlich dargestellt.

Technischer Hintergrund und Motivation

Nach 17 Jahren intensiver Tipp-Erfahrung und dem Experimentieren mit meiner neuen HotSwap 60%-Tastatur – inklusive einer mit Kork gedämmten Unterlage – stellte sich die Frage: Wie schnell kann ich wirklich tippen? Auf der Suche nach einem passenden Tool stieß ich auf „Write or Die“, das jedoch nicht mehr aktiv weiterentwickelt wurde. Andere Lösungen erforderten oft eine aufwendige Registrierung – etwas, das mir nicht zusagte. Schreibabenteuer DemusOpalium entstand also als offene, flexible Plattform, um den Spaß am Schreiben mit einem Belohnungssystem und verschiedenen Herausforderungen zu kombinieren.
Plattformen und Nutzung

    PC (Tastatur):
    Der Hauptfokus liegt auf der PC-Version, die eine umfassende Nutzung von Tastatur und Maus ermöglicht. Alle Spielmodi, das Belohnungssystem, der Shop und das Profilmanagement sind für den PC optimiert.

    Mobile Version:
    Eine vollständig responsive Version sorgt dafür, dass du das Spiel auch auf Smartphones problemlos spielen kannst – ideal für unterwegs, auch wenn der Schwerpunkt auf dem PC liegt.

Beim Beenden einer Session wird ein Score basierend auf der Anzahl geschriebener Wörter, Tippgeschwindigkeit (WPM), Fehlern und weiteren Boni berechnet. Dementsprechend erhältst du Wissenspunkte, die du im Shop einsetzen kannst – und beim Level-Up gibt es zusätzlich Belohnungen.
Open Source & Community

Der gesamte Code ist offen einsehbar und dient als Basis für weitere Verbesserungen und Erweiterungen. Wir freuen uns über Feedback, Bug-Meldungen und Beiträge der Community!

Besonderer Dank:
Dieses Projekt wurde in enger Zusammenarbeit mit einer wunderbaren KI entwickelt – sie liefert immer wieder kreative Ideen und sorgt dafür, dass wir gemeinsam großartigen Code erstellen. Ein großes Dankeschön an diese inspirierende Unterstützung!

Vielen Dank, dass du Schreibabenteuer DemusOpalium ausprobierst – viel Spaß beim Schreiben, Tippen und Entdecken aller neuen Features!
