TastaturAbenteuer – Schreibabenteuer DemusOpalium

TastaturAbenteuer (auch bekannt als Schreibabenteuer DemusOpalium) ist ein interaktives Schreibspiel, das dir dabei hilft, deine Tippfähigkeiten zu verbessern und deine Schreibkunst zu optimieren. Unser erstes Open-Source-Projekt entstand aus reiner Freude an der Technik und dem Wunsch, ein nützliches Tool zu schaffen – ganz ohne Anmeldezwang, damit jeder ungehindert loslegen kann.
Hintergrund

Nach 17 Jahren intensiver Tipp-Erfahrung und dem Experimentieren mit meiner neuen HotSwap 60%-Tastatur – inklusive einer mit Kork gedämmten Unterlage – stellte sich die Frage: Wie schnell kann ich wirklich tippen? Auf der Suche nach einem passenden Tool stieß ich auf „Write or Die“, das jedoch nicht mehr aktiv weiterentwickelt wurde. Andere Lösungen erforderten oftmals eine aufwendige Registrierung, was mir nicht zusagte.

Als Legastheniker und Mensch, der mit MS lebt, nutze ich zudem KI-Unterstützung für die Textgestaltung und Grammatik. Diese persönlichen Erfahrungen flossen direkt in die Entwicklung von TastaturAbenteuer ein, um ein Tool zu schaffen, das authentisch und praxisnah ist.
Hauptfunktionen

    Verschiedene Spielmodi:

        Freewrite: Entfalte deine Kreativität ohne Einschränkungen.

        Adventure: Stelle dich spannenden Bosskämpfen, sammle EPIC-Boni und meistere herausfordernde Schreibaufgaben.

        Copy Challenge: Tippe vorgegebene Sätze exakt nach, sammle Punkte und klettere in der Rangliste nach oben.

        Hardcore: Teste deine Fähigkeiten unter extremen Bedingungen – hier zählt jede unterbrochene Pause.

    Anpassbare Themes und Schriftarten:

        Nutze verschiedene Farbschemata (Dark, Light, Vintage) und wähle die für dich angenehmste Schriftart. Wir haben bewusst vorerst auf Bilder, Sounds und Musik verzichtet, um den Fokus auf Inhalt und Funktionalität zu legen. Es geht darum, dass du nicht unnötig abgelenkt wirst – Lernen und Präzision stehen im Mittelpunkt.

    Detaillierte Statusleiste:

        Behalte alle wichtigen Informationen im Blick: Zeitlimit, Wortanzahl, XP, Niveau, WPM (Wörter pro Minute) und APM (Tastenanschläge pro Minute).

    Belohnungen und Erfolge:

        Sammle Erfolge, schalte coole Rewards frei und vergleiche deine Leistung in der Highscore-Liste mit anderen Spielern.

    Modernes, ansprechendes Design:

        Stilvolle Animationen, ein klares Layout und intuitive Bedienelemente sorgen für ein motivierendes und spaßiges Trainingserlebnis.

Code-Architektur & Aufbau

Für alle technisch Interessierten bieten wir einen detaillierten Einblick in den Aufbau des Codes:

    Projektstruktur:

        /src
        Hier findest du den gesamten Quellcode, aufgeteilt in mehrere Module, die jeweils einzelne Aspekte des Spiels abdecken.

            /core – Enthält die Hauptlogik des Spiels, beispielsweise die Spielmodi, die Steuerung und das Punktesystem.

            /ui – Verantwortlich für das Frontend, das Layout, die Statusleiste sowie die dynamische Anzeige von Text und Animationen.

            /utils – Hilfsfunktionen und gemeinsame Logik, die in mehreren Bereichen zum Einsatz kommen (z. B. Timer, Event-Handler und Konfigurationsparser).

    Modulare Entwicklung:

        Jedes Modul wurde so konzipiert, dass es unabhängig getestet und bei Bedarf erweitert werden kann. Dies gewährleistet eine hohe Flexibilität und erleichtert das Hinzufügen neuer Features oder das Optimieren bestehender Funktionen.

    Saubere Code-Struktur:

        Klare Trennung von Logik und Darstellung: Die Trennung zwischen Geschäftslogik (Gameplay, Punktesystem, Events) und UI-Komponenten (Animationen, Layout) steht im Vordergrund. Dadurch können Entwickler schnell den Überblick gewinnen und spezifische Komponenten isoliert bearbeiten.

        Kommentare und Dokumentation: Der Code ist ausführlich kommentiert. Ein README-Dokument im Hauptverzeichnis bietet eine Übersicht über die Module, ihre Funktion und die Interaktion untereinander.

    Build- und Deployment-Tools:

        Das Projekt nutzt moderne Tools und Skripte, um den Build-Prozess, das Testing und das Deployment zu automatisieren. Dies gewährleistet eine konsistente Codebasis und erleichtert zukünftige Beiträge durch die Community.

    Best Practices:

        Es werden gängige Designmuster (wie MVC oder modulare Architektur) angewandt, um eine saubere und wartbare Codebasis zu gewährleisten. Dies erleichtert auch erfahrenen Entwicklern, sich schnell in den Code einzuarbeiten und den Entwicklungsprozess aktiv mitzugestalten.

Zielgruppe

TastaturAbenteuer richtet sich an alle, die ihre Schreibfähigkeiten verbessern möchten – egal ob Anfänger oder Fortgeschrittene. Die Vielfalt der Modi und Anpassungsmöglichkeiten bietet jedem Spieler genau die richtige Herausforderung. Insbesondere technisch versierte Nutzer und Entwickler finden in der übersichtlichen Code-Struktur und den klar getrennten Modulen wertvolle Einblicke und Anknüpfungspunkte für eigene Erweiterungen.
Projektziele

    Verbesserung der Tippgeschwindigkeit:

        Trainiere deine Fingerfertigkeit und steigere deine Geschwindigkeit für Alltag und Beruf.

    Steigerung der Schreibgenauigkeit:

        Lerne, Fehler zu minimieren und Sätze exakt wiederzugeben.

    Spaß am Lernen:

        Durch spannende Herausforderungen und kreative Modi wird das Üben zur unterhaltsamen Erfahrung.

    Transparente Entwicklung:

        Als Open-Source-Projekt fördern wir den Austausch mit der Community, sodass jeder seine Ideen einbringen und von einer klar strukturierten Codebasis profitieren kann.

Diese umfassende Beschreibung soll nicht nur den Inhalt und die Funktionen von TastaturAbenteuer erläutern, sondern auch einen detaillierten Einblick in den strukturierten Aufbau des Codes bieten. Wir glauben daran, dass eine transparente und gut dokumentierte Codebasis der Schlüssel zur kontinuierlichen Verbesserung und zum gemeinsamen Erfolg ist.

Mit viel Herzblut, persönlicher Note und dem Anspruch, ein effektives Lernwerkzeug zu schaffen, laden wir dich ein, TastaturAbenteuer auszuprobieren – sowohl als Spieler als auch als Entwickler!
