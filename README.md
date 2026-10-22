# Kommas Zählrahmen und Kommas Bimmelbahn

Eine ruhige Lern-App für kleine Kinder im Aquarell- und Zeichenstift-Stil. Die Kinder sehen ein Bild, stellen die Menge an einem virtuellen Zählrahmen ein und sammeln dabei Sterne. Für jeweils 10 Sterne gibt es eine Fahrkarte für **Kommas Bimmelbahn**, ein kleines Zugspiel mit Katze Komma als Lokführerin.

Alles steckt in einer einzigen HTML-Datei. Es gibt keine externen Schriften, Bibliotheken oder Dienste.

---

## Inhalt

- `index.html`: die komplette App (Zählrahmen und Bimmelbahn)
- `README.md`: diese Datei

---

## Für Kinder: so wird gespielt

### Startseite

Fünf große Bildkarten führen zum Spiel:

| Karte | Was passiert |
|---|---|
| **Zählen** | Tiere im Bild zählen und am Zählrahmen zeigen |
| **Dazu** | Erst die Tiere zeigen, dann kommen neue dazu, am Ende die passende Zahl antippen |
| **Weg** | Erst die Tiere zeigen, dann gehen einige weg, am Ende die passende Zahl antippen |
| **Verliebte Zahlen** | Zehn Plätze, einige sind besetzt: erst die Dinge zeigen, dann bis 10 auffüllen, am Ende antippen, wie viele gefehlt haben. Die beiden Zahlen „verlieben“ sich mit einer Herz-Animation. |
| **Frei** | Frei mit den Kugeln spielen (breite Karte unter den vier Bildkarten) |

Darunter liegt die Karte **Kommas Bimmelbahn** mit den gesammelten Fahrkarten. Ganz unten stehen Links zu Impressum, Datenschutz und Lizenz.

Oben links führt der **Haus-Knopf** zur Startseite prima.kommakatze.de (offline ausgeblendet). Oben rechts sitzt der **Vollbild-Knopf** (vier Ecken). Er erscheint auch im Spiel und in der Bahn und schaltet Vollbild an und aus. Auf Geräten, die kein Vollbild für Webseiten erlauben (z. B. iPhone), ist er ausgeblendet. Auf dem iPhone geht es stattdessen über „Zum Home-Bildschirm“.

### Zählrahmen bedienen

- **Antippen:** Das Kind tippt die Kugel an, bis zu der gezählt wird. Alle Kugeln davor gehen mit.
- **Wischen** über die Kugeln funktioniert auch.
- **Zurücknehmen:** Tippt das Kind die letzte Kugel noch einmal an, wird eine weggenommen.
- **Prüfen:** Die App prüft von selbst. Es gibt keine Fehlermeldungen, nur nach einer Pause den sanften Hinweis „Zähl noch einmal nach“.
- **Verbindung zum Bild:** Jedes gezählte Tier bekommt im Bild einen farbigen Punkt. So ist die Eins-zu-eins-Zuordnung sichtbar.
- **Mitwachsende Zahlen:** Im Zwanzigerraum bleiben die ersten Aufgaben bis 10 und wachsen danach bis 20. Im Elternmenü lässt sich stattdessen eine feste Stufe wählen (siehe unten).

### Sterne und Fahrkarten

- Jedes gelöste Bild bringt einen Stern ins Sternenglas.
- Beim zehnten Stern gibt es eine Fahrkarte. Das Kind wählt:
  - **Einsteigen:** sofort mit der Bimmelbahn fahren.
  - **Sammeln:** die Fahrkarte in die Mappe auf der Startseite legen.
- Eine Fahrt kostet eine Fahrkarte. Abgebucht wird erst beim Losfahren.
- Am Ende einer Fahrt gibt es kein „Nochmal fahren“. So lässt sich das Rechnen nicht umgehen: Weitere Fahrten gibt es nur mit einer neuen Fahrkarte oder als Freifahrt über das Elternmenü.
- Mit dem 🏠-Knopf geht es jederzeit zurück zum Zählrahmen.

### Vorlesen

- Vorlesen ist standardmäßig **aus**.
- Bei jeder Aufgabe gibt es einen **Lautsprecher-Knopf**. Er liest den aktuellen Satz einmal vor, auch wenn Vorlesen im Elternmenü aus ist.
- Dauerhaft einschalten lässt sich Vorlesen im Elternmenü. Die Einstellung gilt dann auch für die Bimmelbahn.
- Es werden **nur Stimmen genutzt, die fest auf dem Gerät installiert sind**. Gibt es keine eingebaute deutsche Stimme (z. B. in Chrome am PC ohne Windows-Sprachpaket), sind Lautsprecher-Knopf und Vorlese-Kachel ausgeblendet.

---

## Für Erwachsene: Elternmenü

Das Elternmenü öffnet sich erst, wenn man den Zahnrad-Knopf **2 Sekunden gedrückt hält**. Beim Halten füllt sich der Knopf langsam. Das gilt auf der Startseite, in der Bahn (Zahnrad oben rechts) und auf dem Startbildschirm der Bahn.

Zählrahmen und Bimmelbahn teilen sich **ein gemeinsames Elternmenü**. Wird es während einer Fahrt geöffnet, pausiert der Zug, und oben erscheint zusätzlich die Gruppe **„Diese Fahrt“**: Ohne Aufgaben · Mit Aufgaben.

Die Kachel **„Freifahrt starten“** (Gruppe „Bimmelbahn: Freifahrt“) startet eine Fahrt ohne Fahrkarte. Sie ist der einzige Weg, ohne Fahrkarte zu fahren.

Alle Einstellungen sind Bildkacheln. Die gewählte Kachel hat einen grünen Haken.

| Bereich | Auswahl | Standard |
|---|---|---|
| Kugeln | **Drehen** (Abaco-Prinzip) · **Schieben** (klassischer Abakus) | Drehen |
| Größe | bis 20 · bis 100 | bis 20 |
| Stufe (nur bis 20) | Mitwachsend · 1 bis 5 · 5er-Übergang · 1 bis 10 · 10er-Übergang · 1 bis 20 | Mitwachsend |
| Anordnung | parallel · in Reihe | parallel |
| Farben (nur bei „Drehen“) | 3 Farben (grau/blau/rot) · 2 Farben (grau/blau) | 3 Farben |
| Bimmelbahn: Fahrtlänge je Fahrkarte | 1 · 2 · 5 Bahnhöfe · Freie Fahrt (∞) | 1 Bahnhof |
| Vorlesen | an · aus | aus |
| Töne | an · aus | an |
| Fortschritt auf diesem Gerät | Merken · Nicht merken | Abfrage beim ersten Start |

### Stufen im Zahlenraum bis 20

| Stufe | Zählen | Dazu | Weg |
|---|---|---|---|
| 1 bis 5 | 1–5 | Ergebnis höchstens 5, z. B. 2 + 3 | Start höchstens 5, z. B. 4 − 1 |
| 5er-Übergang | 6–10 (Kraft der Fünf) | über die 5, z. B. 3 + 4, 4 + 5 | über die 5 zurück, z. B. 7 − 3, 9 − 5 |
| 1 bis 10 | 1–10 | Ergebnis höchstens 10 | Start höchstens 10 |
| 10er-Übergang | 11–19 | über die 10, z. B. 8 + 5, 7 + 6 | über die 10 zurück, z. B. 13 − 5, 15 − 7 |
| 1 bis 20 | 2–20 | Ergebnis höchstens 20, zweite Zahl bis 9 | Start höchstens 20, weg bis 9 |

Ergebnis ist nie 0. Die Auswahlzahlen am Ende bleiben im Zahlenraum der Stufe.

Die **verliebten Zahlen** gehen unabhängig von der Stufe immer bis 10 (1 + 9 bis 9 + 1). Das Bild zeigt zehn Plätze in 2 × 5, wie ein Eierkarton oder zehn Seerosenblätter. Beim Auffüllen erscheinen die fehlenden Dinge im Bild.

### Die zwei Kugel-Prinzipien

- **Drehen (Abaco-Prinzip):**
  - Die Kugeln drehen sich auf der Stange.
  - Was im Bild da ist, wird blau. Was dazukommt oder weggeht, wird rot.
  - Bei zwei Farben dreht man das Weggehende zurück auf grau.
- **Schieben (Abakus-Prinzip):**
  - Die Kugeln haben feste rot-weiße Fünferfarben.
  - Gezählte Kugeln werden nach links geschoben, Weggehende zurück nach rechts.
  - Bei „Dazu“ bleibt eine kleine Lücke zwischen den ersten und den neuen Kugeln.
  - Im Modus „Frei“ ist jede Stange einzeln verschiebbar.

### Zahlenraum bis 100

Im Hunderterraum zeigen die Bilder Eier in Zehnerkartons. So wird das Bündeln sichtbar. Der Zählrahmen hat dann 10 × 10 Kugeln mit Lücke zwischen den 5 × 5-Blöcken, in Reihe als fünf Zwanzigerreihen.

### Bimmelbahn

- Jede Fahrt startet standardmäßig **ohne Aufgaben** über **1 Bahnhof** pro Fahrkarte.
- „Mit Aufgaben“ (Hupen, beim Stern halten, Weiche wählen) ist auf dem Startbildschirm der Bahn wählbar.
- Die Fahrtlänge lässt sich im gemeinsamen Elternmenü einstellen.

---

## Datenschutz

- Keine personenbezogenen Daten, keine Cookies, kein Tracking, keine Anmeldung.
- Keine Inhalte von fremden Servern.
- **Speichern nur mit Einwilligung** (wie beim Silbenexpress): Beim ersten Start fragt die App „Eine Frage an die Erwachsenen“: *Ja, merken* oder *Nein, nichts speichern*. Rechtsgrundlage Art. 6 Abs. 1 lit. a DSGVO, § 25 Abs. 1 TDDDG.
  - Bei *Ja* werden im Browser (`localStorage`) gespeichert: die Einwilligung (`kommas-einwilligung-v1`), die Einstellungen (`kommas-zaehlrahmen-v4`) sowie Sterne und Fahrkarten (`kommas-fahrkarten-v1`).
  - Bei *Nein* wird nichts gespeichert. Die App funktioniert vollständig, vergisst den Stand aber beim Schließen und fragt beim nächsten Start erneut.
  - Widerruf jederzeit im Elternmenü mit *Nicht merken*: Alle gespeicherten Angaben werden sofort gelöscht.
- Die vollständige **Datenschutzerklärung** (Verantwortlicher, GitHub-Pages-Protokolle, Speicherung auf dem Gerät, Vorlesen, Kinder, externe Links, Rechte, Aufsichtsbehörde BayLDA) steht in der App unter „Datenschutz“, ebenso **Impressum** und **Lizenz**.
- „Vorlesen“ nutzt ausschließlich lokale Stimmen des Geräts (`localService`). Dabei werden keine Texte und keine IP-Adresse an Dritte übertragen. Fehlt eine solche Stimme, ist Vorlesen nicht verfügbar. Zusätzlich ist Vorlesen ab standardmäßig aus.

---

## Lizenz

Kommas Zählrahmen & Kommas Bimmelbahn von Sebastian Wolf, lizenziert unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de). Du darfst die App teilen und bearbeiten, wenn du den Namen nennst und unter gleichen Bedingungen weitergibst.

**Transparenzhinweis:** Programmiert mit Unterstützung von KI (Claude, Anthropic). Idee, Inhalte und fachliche Prüfung: Sebastian Wolf.
