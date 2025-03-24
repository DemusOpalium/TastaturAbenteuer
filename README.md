TastaturAbenteuer – Schreibabenteuer DemusOpalium

TastaturAbenteuer (auch bekannt als Schreibabenteuer DemusOpalium) ist ein interaktives Schreibspiel, das dir dabei hilft, deine Tippfähigkeiten zu verbessern und deine Schreibkunst zu optimieren. Dieses Open-Source-Projekt entstand aus reiner Freude an der Technik und dem Wunsch, ein nützliches Tool zu schaffen – ganz ohne Anmeldezwang, sodass jeder ungehindert loslegen kann.
Inhaltsverzeichnis

    Hintergrund

    Features & Spielmodi

    Fokus auf Inhalt und Funktionalität

    Code-Struktur und Aufbau

    Installation und Nutzung

    Beitrag und Weiterentwicklung

    Lizenz

Hintergrund

Nach 17 Jahren intensiver Tipp-Erfahrung und dem Experimentieren mit meiner neuen HotSwap 60%-Tastatur – inklusive einer mit Kork gedämmten Unterlage – stellte sich die Frage: Wie schnell kann ich wirklich tippen? Auf der Suche nach einem passenden Tool stieß ich auf „Write or Die“, das jedoch nicht mehr aktiv weiterentwickelt wurde. Andere Lösungen erforderten oftmals eine aufwendige Registrierung – etwas, das mir nicht zusagte.

Als Legastheniker und jemand, der mit MS lebt, nutze ich zudem KI-Unterstützung bei der Textgestaltung und Grammatik. Diese persönlichen Erfahrungen flossen direkt in TastaturAbenteuer ein, um ein authentisches und praxisnahes Tool zu schaffen, das jedem hilft, seine Tippfähigkeiten zu trainieren.
Features & Spielmodi

TastaturAbenteuer bietet eine Vielzahl von Modi und Funktionen, die für ein motivierendes Schreiberlebnis sorgen:

    Verschiedene Spielmodi:

        Freewrite: Entfalte deine Kreativität ohne Einschränkungen.

        Adventure: Tritt in spannenden Bosskämpfen gegen den „Wort Boss“ an, sammle EPIC-Boni und meistere herausfordernde Schreibaufgaben.

        Copy Challenge: Tippe vorgegebene Sätze exakt nach, sammle Punkte und steige in der Rangliste auf.

        Hardcore: Teste deine Fähigkeiten unter extremen Bedingungen – jede unterbrochene Pause zählt!

    Anpassbare Themes und Schriftarten:

        Wähle zwischen verschiedenen Farbschemata (Dark, Light, Vintage) und passe die Schriftart an deine Vorlieben an.

    Detaillierte Statusleiste:

        Behalte wichtige Informationen wie Zeitlimit, Wortanzahl, XP, Niveau, WPM (Wörter pro Minute) und APM (Tastenanschläge pro Minute) stets im Blick.

    Belohnungs- und Achievement-System:

        Schalte Erfolge frei, sammle Rewards und vergleiche deine Leistungen in der Highscore-Liste.

    Interaktive UI-Elemente:

        Modernes, ansprechendes Design mit Animationen (unterstützt durch Animate.css) und einer intuitiven Benutzeroberfläche.

Fokus auf Inhalt und Funktionalität

Um den Lern- und Schreiberfolg in den Vordergrund zu stellen, haben wir bewusst auf ablenkende Elemente wie Bilder, Sounds und Musik verzichtet. Der Hauptfokus liegt auf der reinen Textinteraktion und dem Erreichen von Lernzielen – so wird ein effektives Training ohne unnötige Ablenkungen gewährleistet.
Code-Struktur und Aufbau

Obwohl alle Funktionalitäten und Elemente in einer einzigen HTML-Datei zusammengefasst sind, ist der Code klar strukturiert und gut kommentiert, sodass:

    UI-Elemente und Styles:
    Alle CSS-Regeln für Layout, Themes und Animationen sind direkt im <head> eingebunden, was eine einfache Anpassung und Erweiterung ermöglicht.

    JavaScript-Funktionalität:
    Der gesamte Spielablauf – von der Steuerung und den Spielmodi über die Statusanzeige bis hin zu Belohnungen und Leaderboards – wird über eingebettetes JavaScript umgesetzt.

        Interaktive Steuerung: Die Logik zur Bearbeitung der Tastatureingaben, zur Aktualisierung von Zählern (WPM, APM) und zur Steuerung der verschiedenen Spielmodi ist detailliert implementiert.

        Belohnungs- und Achievement-System: Mechanismen zur Erfassung von Erfolgen und zur Anzeige von Fortschritten sind vollständig integriert.

        Boss-Kampf im Adventure-Modus: Dynamische Berechnung der Boss-Gesundheit und Animationen sorgen für ein spannendes Spielerlebnis.

Diese kompakte, zentrale Organisation fördert eine übersichtliche Darstellung aller Funktionen – so, wie es in unserer ursprünglichen Vision vorgesehen war.
Installation und Nutzung

So startest du:

    Repository klonen oder herunterladen:
    Besuche https://github.com/DemusOpaalium/TastaturAbenteuer und lade das Repository herunter.

    Projekt öffnen:
    Öffne die Datei TastaturAbenteuer.html in deinem bevorzugten Browser. Alle Funktionen stehen sofort zur Verfügung – kein Installationsprozess oder zusätzliche Abhängigkeiten notwendig.

    Loslegen:
    Wähle über die Steuerungselemente deinen gewünschten Modus, passe das Theme und die Schriftart an und starte deine Schreib-Session. Teste die verschiedenen Modi, sammle XP und schalte Erfolge frei!

Beitrag und Weiterentwicklung

TastaturAbenteuer ist ein Open-Source-Projekt, das von der Community lebt. Beiträge sind herzlich willkommen!
Wenn du Anregungen, Bugfixes oder neue Features einbringen möchtest, folge diesen Schritten:

    Fork das Repository

    Erstelle einen neuen Branch für deine Änderungen

    Sende einen Pull Request mit einer detaillierten Beschreibung der vorgenommenen Änderungen

Jeder Beitrag hilft dabei, das Projekt weiter zu verbessern und die Schreibkunst auf ein neues Level zu heben.
Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Jeder ist eingeladen, den Code zu verwenden, zu modifizieren und weiterzuverbreiten – solange die Lizenzbedingungen eingehalten werden.

Mit viel Herzblut, persönlicher Note und dem Ziel, ein effektives Lernwerkzeug zu schaffen, laden wir dich ein, TastaturAbenteuer auszuprobieren – sowohl als Spieler als auch als Entwickler. Viel Spaß und Erfolg beim Tippen!
