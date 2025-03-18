<!--
author: Benjamin Pietke
email: pietke@bszbautzen.de
comment: Lernfeld 1 - Mechatronik: Dieser Online-Kurs dient zur Unterstützung im Lernfeld-Unterricht am BSZ Bautzen.
logo: ./bilder/logo-lf1.png
icon: ./bilder/icon-bsz.png
classroom: enable
-->

// Konzeption und generelle Überlegungen
// Der Kurs wird in drei Blöcke geteilt. **Jeder Block soll individuell verfügbar sein bzw. über einen separaten Link zu Beginn des neuen Blocks.**
// Die SuS bearbeiten die Aufgaben individuell in Ihrem Tempo bzw. in Gruppen.
// Die "Schnellen" tun sich am Ende einer Einheit zu einer Leistungsermittlung zusammen
// als Escape-Room gestalten (genially) und erreichtes Level bestimmt Note?

Tutorial:
https://www.twillo.de/edu-sharing/components/render/818f2dd5-b67e-41e2-baa4-dacfe4d1edac?childobject_id=0d6fecfa-5105-4f82-a725-8e027e02d8ec

LIA-Help:
https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1


# Mechatronische Systeme

![Robo Guy](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzJiYndtOXN5d3Rpc3Z0dGlqMXJmdmM4bjR0NXNia2RsYTUybm15bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/2Bht4u8WRFJDi/giphy.gif)

## Einführung

**Herzlich willkommen im Lernfeld 1!** 🚀

Dieser Kurs dient zur Begleitung des Lernfeldunterrichts für **Lernfeld 1 - Analysieren von Funktionszusammenhängen in mechatronischen Systemen**.

Hier werdet ihr zentrale Kompetenzen erwerben, die für die Untersuchung und Analyse technischer Anlagen von entscheidender Bedeutung sind. Ihr lernt nicht nur, relevante Vorschriften und Regelwerke anzuwenden 📜, sondern stellt auch sicher, dass die Anlagen den geltenden Standards entsprechen.

Ein wesentlicher Bestandteil eurer Ausbildung ist das Arbeiten mit technischen Unterlagen. 📚 Ihr werdet die Fähigkeit entwickeln, diese Dokumentationen zu lesen und zu verstehen. Damit seid ihr in der Lage, sie effektiv für die Lösung praktischer Probleme zu nutzen.

Darüber hinaus werdet ihr euch mit der Analyse und Dokumentation von Funktionszusammenhängen beschäftigen. 🔍 Ihr lernt, die Funktionsweise mechatronischer Systeme zu erfassen und mit Hilfe von Blockschaltplänen den Signal-, Stoff- und Energiefluss zu visualisieren. Das wird euer Verständnis für die Systeme erheblich vertiefen.

Ein weiterer wichtiger Aspekt ist die Kommunikation und Teamarbeit. 🤝 Ihr werdet Gespräche über technische Realisierungs­möglichkeiten üben. Dadurch stärkt ihr nicht nur eure Kommunikationskompetenz, sondern auch eure Fähigkeit, in einem Team zu arbeiten – und das auch auf Englisch. 🌍

Nicht zuletzt werdet ihr für die ökologischen und ökonomischen Aspekte mechatronischer Systeme sensibilisiert. 🌱💰 Ihr lernt, nachhaltige Lösungen zu entwickeln und die Auswirkungen eurer Entscheidungen auf die Umwelt und die Wirtschaftlichkeit zu berücksichtigen.

Insgesamt bietet euch Lernfeld 1 eine solide Grundlage für eure spätere Tätigkeit als Mechatroniker. 🔧 Ihr werdet sowohl technische als auch soziale Kompetenzen entwickeln, die in der modernen Arbeitswelt unerlässlich sind. Seid bereit, euch diesen spannenden Herausforderungen zu stellen! 🎉

**Stundenplanung**

| UE | Inhalte |
|----|---------|
|1+2 |  |
|3+4 |  |
|5+6 | Leistungsermittlung |
|7+8 | Auswertung LE und Vertiefung/Übung, **Auswertung "Sozialnote"** |

## Allgemeines zu Mechatronik

Sie haben die beste Entscheidung getroffen: Die Ausbildung zum Mechatroniker!

![Will YES!](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExeDBuNXg5aGZzZnB1ODg3bHluYjNuMWhjN3MxMmozaWl4eW54Mmt5NyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/glvNGHmbZwgrKH4YYA/giphy.gif)

## Gesamt- und Teilsysteme

Bsp. Bearbeitungsstation

## Analyse und Beschreibung

### Hauptfunktionen technischer Systeme

Mechatronische Systeme setzen Energie, Stoff und Informationen um. Dabei steht eine dieser Aufgaben im Vordergrund. Sie ist die Hauptfunktion des Systems. Die Hauptfunktion erfüllt den eigentlichen Zweck eines Systems, für den es entwickelt wurde. Alle anderen Funktionen eines Systems sind Neben- oder Teilfunktionen und sind von der Hauptfunktion abhängig.

Entsprechend der Hauptfunktion werden Maschinen und Geräte unterteilt in:

- Energieumsetzende Systeme, z.B. Elektromotor
- Stoffumsetzende Systeme, z.B. Pumpe
- Informationsumsetzende Systeme, z.B. PC

(TABELLE vom Arbeitsblatt! --> Als learningapp umsetzen oder so?)


### Darstellung als Blockschaltbild

Blockschaltbilder sind eine wichtige Darstellungsform in der Mechatronik, die es ermöglicht, komplexe Systeme auf eine übersichtliche und verständliche Weise zu visualisieren. Diese Diagramme bestehen aus einfachen geometrischen Formen, die verschiedene Komponenten eines Systems repräsentieren, wie Sensoren, Aktuatoren, Steuerungen und Energiequellen.

Der Hauptzweck von Blockschaltbildern ist es, die Funktionalität und die Wechselwirkungen zwischen den einzelnen Systemteilen klar darzustellen. Sie bieten einen abstrahierten Überblick über das Systemverhalten und vereinfachen die Analyse und das Design von mechatronischen Systemen.

Beispiel eines Blockschaltbildes für die Bearbeitungsstation:

``` ascii
+------------+   +---------+   +-------+
|            |   |         |   |       |
| Förderband +-->| Roboter +-->| Fräse |
|            |   |         |   |       |
+------------+   +---------+   +-------+
```

Durch den Einsatz von Blockschaltbildern kann man leichter:

- Systemfunktionen identifizieren: Die verschiedenen Teile und ihre Funktionen werden klar erkennbar.
- Zusammenhänge verstehen: Die Wechselwirkungen zwischen den Komponenten können einfach dargestellt und analysiert werden.
- Fehlerquellen lokalisieren: Probleme können schneller identifiziert werden, da die Abläufe und Verbindungen visuell nachvollziehbar sind.
- Kommunikation und Dokumentation: Die Verständlichkeit der Systeme wird erhöht, was die Kommunikation zwischen Ingenieuren und anderen Fachleuten erleichtert.

**AUFGABE**

Erstellen Sie die Blockschaltbilder für *ein* Teilsystem der Bearbeitungsstation.

### Energie-, Stoff- und Informationsfluss

|                   | Beschreibung | Beispiel           |
|-------------------|--------------|--------------------|
| **Energiefluss**      | Zugeführte Energie (z.B. Strom) wird in verschiedene Energieformen umgewandelt (z.B. Wärme, Bewegung) | Bearbeitungsstation! |
| **Stofffluss**        | Zuführung von Rohteilen für die Produktion von Werkstücken bzw. Stoffen                               | ? |
| **Informationsfluss** | Verarbeitung von Informationen (z.B. Tasten, Bedienfeld) zur Steuerung und Regelung der Anlage        | ? |

## Leistungsermittlung

### Aufgabenstellung

Pfandflaschenautomat

Ergänzen Sie die drei Blockschaltbilder das Pfandflaschenautomats.

(Abbildungen Westermann AH)

### Bewertungskriterien

## Auswertung und Vertiefung

# Technische Berechnungen

## Infos zu dieser Einheit

**Themen:** Beispiel: Arbeitstag in einer Werkstatt/ Fabrik

**Stundenplanung:** Wir arbeiten acht Unterrichtseinheiten (UE) an diesem Themenkomplex. Die Leistungsermittlung erfolgt etwa in der sechsten UE. Anschließend werten wir diese aus und vertiefen unser Wissen weiter.

## Ein Arbeitstag in der Werkstatt

**AUFGABE**

Stellen Sie per Brainstorming eine Auswahl von mindestens sechs Maschinen zusammen, die Sie in einer Werkstatt finden.

### Berechnungen zur Bearbeitungsstation

Aufstellflächen und Volumen, Einheitenvorsätze, Formeln, Roboter (Hubarbeit, Flaschenzug), Gabelstapler, Beleuchtung--> Strompreise, Geschwindigkeiten von Förderbänder

## Wiederholung physikalischer Grundlagen

### Kraft und deren Darstellung

- F=m∙a=[N=(kg∙m)/s^2 ], Erdbeschleunigung g = 9,81 m/s²
- 1 N = 100 g = 1 Tafel Schokolade!, 10 N = 1 kg, 1.000 N = 100 kg
- Kräfte können als Pfeil (Vektor) dargestellt werden

    + Pfeillänge: Größe der Kraft (Kräftemaßstab nötig!)
    + Pfeilspitze: Richtung der Kraft
    + Pfeilrichtung: Wirkungslinie vom Angriffspunkt aus

- Bsp: Zugkraft F = 1200 N wirkt im Winkel von 45° nach links unten
- ! Kraftpfeile mit derselben Wirkungslinie können addiert werden!
- Bsp: Waagerechte Zugkraft F1 = 300 N und F2 = 400 N, Druckkraft F3 = 700 N
- (!Zusammensetzen von Kräften!)

### Drehmoment

- Greifen an einem Hebel Kräfte an, resultiert ein Drehmoment
- M=F∙l=[Nm]
- Einfluss:
    + Größe der Kraft
    + Länge des Hebels
- Goldene Regel der Mechanik: Was an Kraft gespart wird, muss an Weg zugesetzt werden.
- Bsp: Hebelgesetz

### Arbeit

| Mechanisch | Elektrisch |
|------------|------------|
| "Legt ein Körper unter der Einwirkung einer Kraft einen Weg zurück, so wird mechanische Arbeit verrichtet." | "Wird über eine bestimmte Zeit eine elektrische Leistung verbraucht, so wird elektrische Arbeit verrichtet." |
| W = F * s  | W = P * t |

Einheiten für die Arbeit: [Nm = J (Joule) = Ws]

Anwendung: Elektromotor und Generator

(Ergänzung: Energie Ist die Fähigkeit, Arbeit zu verrichten, während Arbeit der Prozess ist, bei dem Energie übertragen oder umgewandelt wird.)

Übung:R+P S.104, A4, A5

### Leistung

Leistung ist die verrichtete Arbeit pro Zeiteinheit. Je schneller die Arbeit verrichtet wird, desto höher ist die Leistung.

P = W / t = [ Ws / s = W ]
ODER
mit W = F * s ergibt sich P = F * s / t = F * v

### Wirkungsgrad

Eine Maschine nimmt immer mehr Leistung auf als sie abgibt.
(Bsp. Verbrennungsmotor)


$ \eta = \frac{P_{ab}}{P_{zu}} $

Je kleiner die Verluste, desto besser ist der Wirkungsgrad.

Gesamtwirkungsgrad: $ \eta_{ges} = \eta_1 \cdot \eta_2 $

Übung: R+P S.112 A2, A6, A9 (uvm. Je nach Zeit)

## Leistungsermittlung

### Aufgabenstellung

Darstellung von Kräften --> als Reel, Podcast

### Bewertungskriterien

## Auswertung und Vertiefung


# Ökologische und Ökonomische Aspekte

## Infos zu dieser Einheit

* **Themen:** Elektroschrott, Arbeitswelt 4.0

* **Stundenplanung:** Wir arbeiten acht bis zehn Unterrichtseinheiten (UE) an diesem Themenkomplex. Die Leistungsermittlung erfolgt etwa in der sechsten UE. Anschließend werten wir diese aus und vertiefen unser Wissen weiter.


## Einwegpfand

**IDEEN:** Videos und Texte als Input, Erstellung Insta-Beitrag mit Canva --> VORAB Bewertungskriterien ausarbeiten!

![Einwegpfand = Müll?](bilder/pfand-muell.png "Bildrechte: CC0 / Pixabay / Hans")

**AUFGABE**

Finden Sie sich in Gruppen aus drei bis vier Personen zusammen. Bearbeiten Sie die folgenden Aufgaben: 

1. Stellen Sie die wichtigsten Unterschiede zwischen Einweg- und Mehrwegpfand gegenüber.
2. Benennen Sie die Bedeutung der folgenden Symbole:

    + ![Einwegpfand](bilder/pfand-einweg.png "Bildrechte: https://einweg-mit-pfand.de/einweg-mit-pfand.html")
    + ![Pfand gehört daneben](bilder/pfand-daneben.png "Bildrechte: https://www.pfand-gehoert-daneben.de")
    + ![Mehrwegpfand](bilder/pfand-mehrweg.png "Bildrechte: https://www.mehrweg.org/mehrwegzeichen/")

3. Formulieren Sie Ziele, die mit der Einführung des Einwegpfandes verfolgt wurden. 
4. Diskutieren Sie im Zweierteam, ob diese Ziele erreicht wurden. Finden Sie Verbesserungsmöglichkeiten und begründen Sie diese.


## Elektroschrott

![Elektroschrott](bilder/e-schrott.png "Bildrechte: IMAGO / Karina Hessland")

### Allgemeines

**Einführung**

Elektroschrott, oder kurz E-Schrott, sind elektrische und elektronische Geräte, die nicht mehr genutzt werden können oder deren Funktionsfähigkeit beeinträchtigt ist. Mit dem rasanten technologischen Fortschritt und der anhaltenden Nachfrage nach neuen Geräten ist das Aufkommen von Elektroschrott zu einem ernsthaften Umweltproblem geworden. Jährlich landen weltweit Millionen Tonnen alter Smartphones, Computer, Haushaltsgeräte und anderer elektronischer Produkte auf Deponien, was nicht nur wertvolle Rohstoffe wie Gold, Kupfer und seltene Erden ungenutzt lässt, sondern auch erhebliche Umweltschäden durch giftige Substanzen verursacht.

Die wiederholte Produktion und der Konsum von Elektronik tragen zur Erschöpfung bedeutender Ressourcen und zur Verschmutzung von Ökosystemen bei. Daher stellt sich die dringende Frage, wie Elektroschrott nachhaltig verwaltet und die darin enthaltenen Rohstoffe effizient recycelt werden können. Innovative Ansätze, wie Pfandsysteme und verbesserte Recyclingtechnologien, sind notwendig, um einen verantwortungsvollen Umgang mit Elektroschrott zu fördern und zukünftige Generationen vor den Folgen der wachsenden E-Abfälle zu schützen.

### Wie sieht es bei dir Zuhause im Schubfach oder in der Garage aus?

1. Steht dir ein PC/Laptop zu Hause zur Verfügung?

- [( )] Ja
- [( )] Nein
- [[?]] Es gibt kein Richtig oder falsch!
**************************************

In Deutschland besitzen laut verschiedenen Statistiken aus den letzten Jahren etwa **80-90% der Haushalte einen Laptop oder einen PC!** **Einbeldnug um ein GIF erweitern!?**

**************************************

2. Hast du Zuhause eine Konsole (Playstation, Switch, etc.)?

- [( )] Ja
- [( )] Nein
- [[?]] Es gibt kein Richtig oder falsch! Klicke auf das Häkchen.
**************************************

Schätzungen zufolge besitzen etwa **40% der Jugendlichen unter 18 Jahren** eine Spielekonsole. **Einbeldnug um ein GIF erweitern!?**

**************************************

3. Wie häufig kaufst du (oder jemand anderes in deiner Familie) dir ein neues Smartphone?

[[alle 3 Jahre]]
- [[?]] Es gibt kein Richtig oder falsch! Klicke auf das Häkchen.
**************************************

Laut verschiedenen Umfragen und Studien liegt die durchschnittliche Nutzungsdauer eines Smartphones häufig bei **etwa 2 bis 3 Jahren**, bevor die Benutzer ein neues Gerät erwerben. Einige Nutzer behalten ihre Smartphones auch länger, während andere häufiger wechseln, insbesondere wenn es um die neuesten Modelle geht. **Einbeldnug um ein GIF erweitern!?**

**************************************

### Pfandsystem für E-Schrott

**AUFGABE**

1. Lesen Sie den Artikel [**Goldgrube Elektroschrott – Macht ein Pfandsystem für Smartphones Sinn?**](https://www.mdr.de/wissen/pfand-auf-smartphone-und-elektroschrott-sinvoll-100.html). [qr-code](https://www.mdr.de/wissen/pfand-auf-smartphone-und-elektroschrott-sinvoll-100.html)
2. Beantworten Sie mithilfe des Artikels die folgenden Fragen:

    + Wie hoch ist der durchschnittliche Elektroschrott pro Kopf in Deutschland?
    + Was sind sogenannte „kritische Rohstoffe“?
    + Wo können kaputte oder ungenutzte Geräte entsorgt werden?
    + Wodurch wird das Recycling von Smartphones erschwert?
    + Warum lohnt es sich trotz des Aufwands Elektroschrott zu recyclen?
    + Welche Vorteile bietet ein Pfandsystem für Elektroschrott?

### Wer recycelt unseren E-Schrott?

Diese Videos sind eine Auswahl für weitereführende Informationen zum Thema Elektroschrott.

!?[Global E-Waste Report: Wohin mit dem Elektroschrott?](https://www.youtube.com/watch?v=P5_edASIcaE)

!?[Elektromülldeponie Agbogbloshie: Leben und arbeiten am verseuchtesten Ort der Welt](https://www.youtube.com/watch?v=07uMQ-J_T14&t=32s)

!?[Ghana: Was passiert mit Europas Schrott?](https://www.youtube.com/watch?v=R1t7ILyM2U4)

!?[Wie aus unserem Elektroschrott in Ghana neue Rohstoffe werden](https://www.youtube.com/watch?v=a0_kSs104SA)

## Leistungsermittlung

### Aufgabenstellung

Hier sollen die SuS sich zusammenfinden und ihre Leute zur Abgabe von E-Schrott motivieren - irgendwie!

**Mit E-Schrott zu richtig viel Schmott**

### Bewertungskriterien

## Auswertung und Vertiefung

