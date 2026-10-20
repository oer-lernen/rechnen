# Kommas Zählrahmen und Kommas Bimmelbahn

Eine ruhige Lern-App für kleine Kinder im Aquarell- und Zeichenstift-Stil. Die Kinder sehen ein Bild, stellen die Menge an einem virtuellen Zählrahmen ein und sammeln dabei Sterne. Für jeweils 10 Sterne gibt es eine Fahrkarte für **Kommas Bimmelbahn**, ein kleines Zugspiel mit Katze Komma als Lokführerin.

Alles steckt in einer einzigen HTML-Datei. Es gibt keine externen Schriften, Bibliotheken oder Dienste.

---

## Inhalt

- `index.html`: die komplette Anwendung (Zählrahmen und Bimmelbahn)
- `README.md`: diese Datei

---

## Für Kinder: so wird gespielt

### Startseite

Vier große Bildkarten führen zum Spiel:

| Karte | Was passiert |
|---|---|
| **Zählen** | Tiere im Bild zählen und am Zählrahmen zeigen |
| **Dazu** | Erst die Tiere zeigen, dann kommen neue dazu, am Ende die passende Zahl antippen |
| **Weg** | Erst die Tiere zeigen, dann gehen einige weg, am Ende die passende Zahl antippen |
| **Frei** | Frei mit den Kugeln spielen |

Darunter liegt die Karte **Kommas Bimmelbahn** mit den gesammelten Fahrkarten.

### Zählrahmen bedienen

- **Antippen:** Das Kind tippt die Kugel an, bis zu der gezählt wird. Alle Kugeln davor gehen mit.
- **Wischen** über die Kugeln funktioniert auch.
- **Zurücknehmen:** Tippt das Kind die letzte Kugel noch einmal an, wird eine weggenommen.
- **Prüfen:** Die App prüft von selbst. Es gibt keine Fehlermeldungen, nur nach einer Pause den sanften Hinweis „Zähl noch einmal nach“.
- **Verbindung zum Bild:** Jedes gezählte Tier bekommt im Bild einen farbigen Punkt. So ist die Eins-zu-eins-Zuordnung sichtbar.
- **Mitwachsende Zahlen:** Im Zwanzigerraum bleiben die ersten Aufgaben bis 10 und wachsen danach bis 20.

### Sterne und Fahrkarten

- Jedes gelöste Bild bringt einen Stern ins Sternenglas.
- Beim zehnten Stern gibt es eine Fahrkarte. Das Kind wählt:
  - **Einsteigen:** sofort mit der Bimmelbahn fahren.
  - **Sammeln:** die Fahrkarte in die Mappe auf der Startseite legen.
- Eine Fahrt kostet eine Fahrkarte. Abgebucht wird erst beim Losfahren.
- Mit dem 🏠-Knopf geht es jederzeit zurück zum Zählrahmen.

### Vorlesen

- Vorlesen ist standardmäßig **aus**.
- Bei jeder Aufgabe gibt es einen **Lautsprecher-Knopf**. Er liest den aktuellen Satz einmal vor, auch wenn Vorlesen im Elternmenü aus ist.
- Dauerhaft einschalten lässt sich Vorlesen im Elternmenü. Die Einstellung gilt dann auch für die Bimmelbahn.
- Es werden **nur Stimmen genutzt, die fest auf dem Gerät installiert sind**. Gibt es keine eingebaute deutsche Stimme (z. B. in Chrome am PC ohne Windows-Sprachpaket), sind Lautsprecher-Knopf und Vorlese-Kachel ausgeblendet. Online-Stimmen werden nie verwendet.

---

## Für Erwachsene: Elternmenü

Das Elternmenü öffnet sich erst, wenn man den Zahnrad-Knopf **3 Sekunden gedrückt hält**. Beim Halten füllt sich der Knopf langsam. Das gilt auf der Startseite, in der Bahn (Zahnrad oben rechts) und auf dem Startbildschirm der Bahn.

Zählrahmen und Bimmelbahn teilen sich **ein gemeinsames Elternmenü**. Wird es während einer Fahrt geöffnet, pausiert der Zug, und oben erscheint zusätzlich die Gruppe **„Diese Fahrt“**: Ohne Aufgaben · Mit Aufgaben.

Die Kachel **„Freifahrt starten“** (Gruppe „Bimmelbahn: Freifahrt“) startet eine Fahrt ohne Fahrkarte. Sie ist der einzige Weg, ohne Fahrkarte zu fahren.

Alle Einstellungen sind Bildkacheln. Die gewählte Kachel hat einen grünen Haken.

| Bereich | Auswahl | Standard |
|---|---|---|
| Kugeln | **Drehen** (Abaco-Prinzip) · **Schieben** (klassischer Abakus) | Drehen |
| Größe | bis 20 · bis 100 | bis 20 |
| Anordnung | parallel · in Reihe | parallel |
| Farben (nur bei „Drehen“) | 3 Farben (grau/blau/rot) · 2 Farben (grau/blau) | 3 Farben |
| Bimmelbahn: Fahrtlänge je Fahrkarte | 1 · 2 · 5 Bahnhöfe · Freie Fahrt (∞) | 1 Bahnhof |
| Vorlesen | an · aus | aus |
| Töne | an · aus | an |

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

- Keine personenbezogenen Daten, keine Cookies, kein Tracking, keine Anmeldung, keine Inhalte von fremden Servern.
- Im Browser (`localStorage`) werden nur lokal gespeichert:
  - Einstellungen (`kommas-zaehlrahmen-v4`)
  - Sterne und Fahrkarten (`kommas-fahrkarten-v1`)
- Zum Zurücksetzen genügt es, die Websitedaten im Browser zu löschen.
- „Vorlesen“ nutzt ausschließlich lokale Stimmen des Geräts (`localService`). Dabei werden keine Texte und keine IP-Adresse an Dritte übertragen. Fehlt eine solche Stimme, ist Vorlesen nicht verfügbar. 

---

## Lizenz

Kommas Zählrahmen und Kommas Bimmelbahn von Sebastian Wolf, lizenziert unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de). Du darfst die App teilen und bearbeiten, wenn du den Namen nennst und unter gleichen Bedingungen weitergibst.

## Impressum

Sebastian Wolf
Graf-Leopold-Ring 2
94099 Ruhstorf a.d.Rott
E-Mail: s.w.oer@outlook.de
