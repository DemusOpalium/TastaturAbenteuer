Schreibabenteuer DemusOpalium / Writing Adventure DemusOpalium / Mchezo wa Kuandika DemusOpalium

    Hinweis: Dieses Projekt ist ein Open‑Source-Schreibspiel, das sich noch in der Entwicklung befindet. Wir freuen uns über Feedback, Bug‑Meldungen und Beiträge der Community!



######################  Deutsch -  Einleitung  ######################

Schreibabenteuer DemusOpalium ist ein Open‑Source-Schreibspiel, in dem du in variablen Zeitmodi (1–5 Minuten) spannende Schreib‑Challenges meisterst – sei es kreativ, präzise oder unter hohem Druck. Das Spiel richtet sich vor allem an PC‑Nutzer mit Tastatur, bietet aber auch eine voll responsive Version für mobile Geräte.
Hauptfunktionen & Spielmodi

    Freewrite: Kreatives Schreiben ohne Strafe.

    Hardcore: Jeder Fehler oder jede Inaktivität löscht den Text.

    Adventure: Stelle dich dem „Wort Boss“ und kämpfe mit deinen geschriebenen Wörtern.

    Copy Challenge: Tippe vorgegebene Sätze exakt nach – das Spiel startet zuverlässig per Enter‑Taste, und beim Reset werden stets neue Sätze generiert.

    Kreativmodus: Erhalte inspirierende Schreibimpulse, um deine Kreativität anzukurbeln.

Belohnungssystem & Erfolge

    Erreiche bestimmte Meilensteine (z. B. eine bestimmte Wortanzahl) und schalte Erfolge frei.

    Verdiene Rewards und Abzeichen (z. B. spezielle Emoji‑Rewards, Schriftfarben etc.), die im Shop erworben werden können.

Shop & Inventar

    Kaufe kosmetische Upgrades wie neue Profilbilder, Glücksbringer und weitere Icons mit deinen verdienten Wissenspunkten.

    Das System wurde hinsichtlich Anzeige und Bedienbarkeit optimiert – Icons und Buttons passen sich sowohl an PC als auch mobile Geräte an.

Profil‑Sicherheit

    Beim Speichern deines Profils wird eine einfache Checksumme (basierend auf deinen Wissenspunkten plus einem geheimen Schlüssel) erzeugt und mitgespeichert.

    Beim Laden des Profils wird diese Checksumme überprüft – Unstimmigkeiten werden als möglicher Betrugsversuch gemeldet.

    Neu: Der Mechanismus berücksichtigt jetzt alle relevanten Werte (z. B. dein Inventar an Glücksbringern).

Copy Challenge Optimierungen

    Verbesserte Logik bei den Copy‑Messages: Das Spiel startet zuverlässig per Enter‑Taste, sobald der Start-Hinweis im Texteingabefeld erscheint.

    Das Reset‑Problem im Copy‑Modus wurde behoben – neue Sätze werden stets generiert.

Neue Features & Erweiterungen

    Namensänderung im Profil: Ein Eingabefeld und Button ermöglichen es, den Profilnamen direkt im Spiel zu ändern – die Änderung wird sofort im Profilbereich angezeigt.

    Terminologie-Anpassungen:

        „Credits“ wurden in Wissenspunkte umbenannt.

        „Cursoren“ wurden durch Glücksbringer ersetzt – alle zugehörigen Variablen, Shop‑Items und Anzeigeelemente wurden angepasst.

    Neue Kategorie "Code/Python":

        Easy (25 Beispiele): Basisbefehle, Variablenzuweisungen, Schleifen und einfache Ausgaben.

        Normal (15 Beispiele): Funktionen, Bedingungen, List Comprehensions, Dateioperationen und Klassen.

        Hard (10 Beispiele): Anspruchsvolle Beispiele wie Merge‑Sort, DataFrame‑Operationen, Dekoratoren, Singleton‑Pattern, asynchrone Programmierung und Generatoren – humorvoll und übersichtlich dargestellt.


Technischer Hintergrund & Motivation

Nach 17 Jahren intensiver Tipp-Erfahrung und dem Experimentieren mit meiner neuen HotSwap 60%-Tastatur (inklusive einer mit Kork gedämmten Unterlage) stellte sich die Frage: Wie schnell kann ich wirklich tippen? Auf der Suche nach einem passenden Tool stieß ich auf „Write or Die“, das jedoch nicht mehr aktiv weiterentwickelt wurde. Schreibabenteuer DemusOpalium entstand als offene, flexible Plattform, um den Spaß am Schreiben mit einem Belohnungssystem und verschiedenen Herausforderungen zu kombinieren.
Plattformen & Nutzung

    PC (Tastatur): Optimiert für die Nutzung von Tastatur und Maus. Alle Spielmodi, das Belohnungssystem, der Shop und das Profilmanagement sind für den PC optimiert.

    Mobile Version: Eine vollständig responsive Version ermöglicht das Spielen auch auf Smartphones – ideal für unterwegs.

Beim Beenden einer Session wird ein Score basierend auf der Anzahl geschriebener Wörter, Tippgeschwindigkeit (WPM), Fehlern und weiteren Boni berechnet. Du erhältst Wissenspunkte, die im Shop ausgegeben werden können – sowie zusätzliche Belohnungen beim Level‑Up.
Open Source & Community

Der gesamte Code ist offen einsehbar und dient als Grundlage für weitere Verbesserungen und Erweiterungen. Wir freuen uns über Feedback, Bug‑Meldungen und Community‑Beiträge!
Besonderer Dank

Dieses Projekt wurde in enger Zusammenarbeit mit einer wunderbaren KI entwickelt, die uns immer wieder kreative Ideen liefert und dazu beiträgt, großartigen Code zu erstellen. Vielen Dank für diese inspirierende Unterstützung!








######################  English  -  Introduction  ######################

Writing Adventure DemusOpalium is an open‑source typing game where you tackle exciting writing challenges in variable time modes (1–5 minutes) – whether you’re being creative, precise, or under intense pressure. Designed primarily for PC users with a keyboard, the game also offers a fully responsive version for mobile devices.
Main Features & Game Modes

    Freewrite: Creative writing without penalty.

    Hardcore: Every mistake or period of inactivity deletes your text.

    Adventure: Face the “Word Boss” and battle using your typed words.

    Copy Challenge: Type given sentences exactly as shown – with improved logic, the game reliably starts with the Enter key and always generates new sentences upon reset.

    Creative Mode: Enjoy inspiring writing prompts to boost your creativity.

Reward System & Achievements

    Unlock achievements when you reach specific milestones (e.g., a certain word count).

    Earn rewards and badges (such as special emoji rewards, font colors, etc.) that can be purchased in the shop.

Shop & Inventory

    Buy cosmetic upgrades like new profile images, charms, and other icons using your earned Knowledge Points.

    The interface has been optimized for both PC and mobile devices, with improved icon and button designs.

Profile Security

    To prevent tampering (e.g., by directly editing the JSON file), a simple checksum (based on your Knowledge Points plus a secret key) is generated and saved when you save your profile.

    When loading your profile, this checksum is verified – any discrepancies are flagged as potential cheating.

    New: The mechanism now takes all relevant values (e.g., your inventory of charms) into account.

Copy Challenge Optimizations

    Improved logic for copy messages: the game now reliably starts with the Enter key when the start prompt appears in the text input field.

    The reset issue in Copy Mode has been fixed – new sentences are always generated.

New Features & Enhancements

    Profile Name Change: An input field and button allow you to update your profile name directly in the game – the change is immediately reflected in your profile area.

    Terminology Adjustments:

        “Credits” have been renamed to Knowledge Points.

        “Cursors” have been replaced by Charms – with all related variables, shop items, and display elements updated accordingly.

    New "Code/Python" Category:

        Easy (25 examples): Basic commands, variable assignments, loops, and simple outputs.

        Normal (15 examples): Functions, conditions, list comprehensions, file operations, and classes.

        Hard (10 examples): Challenging examples such as merge sort, DataFrame operations, decorators, the singleton pattern, asynchronous programming, and generators – presented humorously and clearly.

Technical Background & Motivation

After 17 years of intensive typing experience and experimenting with my new HotSwap 60%-keyboard (complete with a cork-dampened base), I asked myself: How fast can I really type? On the search for a suitable tool, I discovered “Write or Die,” which is no longer actively developed. Writing Adventure DemusOpalium was created as an open, flexible platform to combine the fun of writing with a reward system and various challenges.
Platforms & Usage

    PC (Keyboard): Optimized for full use of keyboard and mouse. All game modes, the reward system, shop, and profile management are PC‑optimized.

    Mobile Version: A fully responsive version ensures you can play the game seamlessly on smartphones – perfect for on‑the‑go use.

After a session, your score is calculated based on the number of words written, typing speed (WPM), errors, and additional bonuses. You earn Knowledge Points that can be spent in the shop – with extra rewards given on level‑up.
Open Source & Community

All code is open source and serves as the foundation for further improvements and enhancements. We welcome feedback, bug reports, and community contributions!
Special Thanks

This project was developed in close collaboration with an amazing AI that continually provides creative ideas and helps us create outstanding code. A big thank you for this inspiring support!







######################  Swahili -  Utangulizi  ######################

Mchezo wa Kuandika DemusOpalium ni mchezo wa kuandika (typing game) wa open‑source ambapo unakabiliana na changamoto za kuandika katika muda tofauti (dakika 1–5) – iwe unaunda, unaandika kwa usahihi, au chini ya shinikizo kubwa. Mchezo umeundwa hasa kwa watumiaji wa PC wenye kibodi, lakini pia unatoa toleo linalobadilika kikamilifu kwa vifaa vya simu.
Vipengele Vikuu & Aina za Mchezo

    Freewrite: Kuandika kwa ubunifu bila adhabu.

    Hardcore: Kosa lolote au kukosa shughuli kunafuta maandishi yako.

    Adventure: Lingana na “Bosi wa Maneno” na pigana kwa kutumia maneno yako yaliyoandikwa.

    Copy Challenge: Nakili sentensi zilizoonyeshwa kwa usahihi – kwa sababu ya ubunifu ulioboreshwa, mchezo huanza kwa ufahamu wa kitufe cha Enter na kila reset sentensi mpya huundwa.

    Creative Mode: Pata msukumo wa kuandika ili kuongeza ubunifu wako.

Mfumo wa Tuzo na Mafanikio

    Fungua mafanikio unapofikia vipengele maalum (kwa mfano, idadi fulani ya maneno).

    Pata tuzo na medali (kama vile emoji maalum, rangi za herufi, nk.) ambazo unaweza kununua katika duka.

Duka & Hazina

    Nunua maboresho ya mwonekano kama picha mpya za wasifu, vibonzo, na icons nyingine kwa kutumia Alama za Maarifa ulizopata.

    Mfumo umeboreshwa kwa ufanisi kwa PC na vifaa vya simu – icons na vitufe vimeboreshwa.

Usalama wa Wasifu

    Ili kuzuia udanganyifu (mfano, kwa kubadilisha faili ya JSON moja kwa moja), checksum rahisi (iliyobainishwa kwa kutumia Alama zako za Maarifa pamoja na ufunguo wa siri) hutengenezwa na kuhifadhiwa wakati wa kuhifadhi wasifu wako.

    Wakati wa kupakia wasifu, checksum hii inakaguliwa – tofauti yoyote inashughulikiwa kama jaribio la udanganyifu.

    Mpya: Mfumo sasa unazingatia thamani zote muhimu (kwa mfano, hazina yako ya vibonzo).

Maboresho ya Copy Challenge

    Logiki iliyoboreshwa kwa ujumbe wa nakili: Mchezo sasa huanza kwa kitufe cha Enter mara tu miongozo ya kuanza huonekana katika sehemu ya kuingiza maandishi.

    Tatizo la reset katika Copy Mode limetatuliwa – sentensi mpya huundwa kila wakati.

Vipengele Vipya na Uboreshaji

    Kubadilisha Jina la Wasifu: Awali hakuwezekana kubadilisha jina la wasifu. Sasa, sehemu ya kuingiza na kitufe kimeongezwa ili urekebishe jina lako moja kwa moja ndani ya mchezo – mabadiliko yanaonekana mara moja katika sehemu ya wasifu.

    Marekebisho ya Terminolojia:

        "Credits" zimebadilishwa kuwa Alama za Maarifa.

        "Cursors" zimenakuliwa na Vibonzo – pamoja na kurekebishwa kwa vigezo, vitu vya duka, na vipengele vya uonyesho.

    Kategoria Mpya "Code/Python":

        Rahisi (25 mifano): Amri za msingi, uelekezaji wa variable, mizunguko, na matokeo rahisi.

        Kawaida (15 mifano): Functions, masharti, list comprehensions, shughuli za faili, na madarasa.

        Gumu (10 mifano): Mifano changamano kama merge sort, shughuli za DataFrame, decorators, singleton pattern, programu zisizo za kusubiri, na generators – zimewasilishwa kwa njia ya ucheshi na wazi.

Maelezo ya Kiufundi na Mmotivation

Baada ya miaka 17 ya uzoefu mkubwa wa kuandika na kujaribu kibodi yangu mpya ya HotSwap 60% (ikiwa na msingi uliosafishwa kwa korki), nilijiuliza: Naweza kuandika kwa kasi kiasi gani kweli? Nilipokuwa nikitafuta zana inayofaa, nilikuta “Write or Die” ambayo haijaendelea kusasishwa. Mchezo wa Kuandika DemusOpalium umeundwa kama jukwaa huria na linalobadilika ili kuchanganya furaha ya kuandika na mfumo wa tuzo pamoja na changamoto mbalimbali.
Majukwaa na Matumizi

    PC (Kibodi): Lengo kuu ni PC, ambapo matumizi ya kibodi na panya yanaangaziwa kikamilifu. Aina zote za mchezo, mfumo wa tuzo, duka, na usimamizi wa wasifu zimeboreshwa kwa PC.

    Toleo la Simu: Toleo linalobadilika kikamilifu linahakikisha unaweza kucheza mchezo hata kwenye simu – bora kwa matumizi ya nje.

Kila baada ya sesheni, score inahesabiwa kulingana na idadi ya maneno yaliyoandikwa, kasi ya kuandika (WPM), makosa, na bonus nyingine. Hivyo, unapata Alama za Maarifa ambazo unaweza kutumia katika duka – pamoja na tuzo za ziada unapopanda kiwango.
Open Source & Jamii

Msimbo mzima uko wazi na unatumika kama msingi wa maboresho na uboreshaji zaidi. Tunakaribisha maoni, taarifa za makosa, na michango kutoka kwa jamii!
Shukrani Maalum

Mradi huu umeundwa kwa ushirikiano wa karibu na AI ya ajabu inayotoa mawazo ya ubunifu na kutusaidia kuunda msimbo bora. Shukrani kubwa kwa msaada huu unaosisimua!

Feel free to modify . Happy coding and writing – enjoy the adventure!
