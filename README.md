# Kommas Zählrahmen & Kommas Bimmelbahn

Eine ruhige Lern-App für kleine Kinder im Aquarell- und Zeichenstift-Stil. Die Kinder sehen ein Bild, stellen die Menge an einem virtuellen Zählrahmen ein und sammeln dabei Sterne. Für jeweils 10 Sterne gibt es eine Fahrkarte für **Kommas Bimmelbahn**, ein kleines Zugspiel mit Katze Komma als Lokführerin.

Alles steckt in einer einzigen HTML-Datei. Es gibt keine externen Schriften, Bibliotheken oder Dienste.

---

## Inhalt

- `kommas-zaehlrahmen.html`: die komplette App (Zählrahmen und Bimmelbahn)
- `README.md`: diese Datei

## Veröffentlichen auf GitHub Pages

1. `kommas-zaehlrahmen.html` ins Repository legen. Soll die App direkt unter der Adresse des Repositorys starten, die Datei in `index.html` umbenennen.
2. Im Repository unter *Settings → Pages* den Branch auswählen und speichern.
3. Nach ein bis zwei Minuten ist die App erreichbar.

Die App funktioniert auch offline, wenn man die Datei einfach im Browser öffnet.

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

- Vorlesen ist ab Werk **aus**.
- Bei jeder Aufgabe gibt es einen **Lautsprecher-Knopf**. Er liest den aktuellen Satz einmal vor, auch wenn Vorlesen im Elternmenü aus ist.
- Dauerhaft einschalten lässt sich Vorlesen im Elternmenü. Die Einstellung gilt dann auch für die Bimmelbahn.

---

## Für Erwachsene: Elternmenü

Das Elternmenü öffnet sich erst, wenn man den Zahnrad-Knopf **5 Sekunden gedrückt hält**. Beim Halten füllt sich der Knopf langsam. Das gilt auf der Startseite, in der Bahn (⚙️) und auf dem Startbildschirm der Bahn.

Alle Einstellungen sind Bildkacheln. Die gewählte Kachel hat einen grünen Haken.

| Bereich | Auswahl | Standard |
|---|---|---|
| Kugeln | **Drehen** (Abaco-Prinzip) · **Schieben** (klassischer Abakus) | Drehen |
| Größe | bis 20 · bis 100 | bis 20 |
| Anordnung | parallel · in Reihe | parallel |
| Farben (nur bei „Drehen“) | 3 Farben (grau/blau/rot) · 2 Farben (grau/blau) | 3 Farben |
| Bimmelbahn: Fahrtlänge | 3 · 5 · 8 Bahnhöfe · Freie Fahrt (∞) | 3 Bahnhöfe |
| Vorlesen | an · aus | aus |
| Töne | an · aus | an |

### Die zwei Kugel-Prinzipien

- **Drehen (Abaco):**
  - Die Kugeln drehen sich auf der Stange.
  - Was im Bild da ist, wird blau. Was dazukommt oder weggeht, wird rot.
  - Bei zwei Farben dreht man das Weggehende zurück auf grau.
- **Schieben (Abakus):**
  - Die Kugeln haben feste rot-weiße Fünferfarben.
  - Gezählte Kugeln werden nach links geschoben, Weggehende zurück nach rechts.
  - Bei „Dazu“ bleibt eine kleine Lücke zwischen den ersten und den neuen Kugeln.
  - Im Modus „Frei“ ist jede Stange einzeln verschiebbar.

### Zahlenraum bis 100

Im Hunderterraum zeigen die Bilder Eier in Zehnerkartons. So wird das Bündeln sichtbar. Der Zählrahmen hat dann 10 × 10 Kugeln mit Lücke zwischen den 5 × 5-Blöcken, in Reihe als fünf Zwanzigerreihen.

### Bimmelbahn

- Jede Fahrt startet ab Werk **ohne Aufgaben** über **3 Bahnhöfe**.
- „Mit Aufgaben“ (Hupen, beim Stern halten, Weiche wählen) ist auf dem Startbildschirm der Bahn wählbar.
- Die Fahrtlänge lässt sich im Elternmenü einstellen: im Zählrahmen oder in der Bahn.

---

## Datenschutz

- Keine personenbezogenen Daten, keine Cookies, kein Tracking, keine Anmeldung.
- Keine Inhalte von fremden Servern.
- Im Browser (`localStorage`) werden nur lokal gespeichert:
  - Einstellungen (`kommas-zaehlrahmen-v4`)
  - Sterne und Fahrkarten (`kommas-fahrkarten-v1`)
- Zum Zurücksetzen genügt es, die Websitedaten im Browser zu löschen.
- „Vorlesen“ nutzt die Sprachausgabe des Geräts bzw. Browsers. Je nach Browser kann der Text dabei an den Anbieter der Stimme übertragen werden. Deshalb ist Vorlesen ab Werk aus.

---

## Technik

- **Eine Datei:** HTML, CSS und JavaScript in einer Datei, ohne Build-Schritt.
- **Grafik:**
  - Der Zählrahmen und die Bilder sind SVG mit Filtern für den Aquarell- und Bleistift-Look.
  - Die Bimmelbahn zeichnet auf einem Canvas.
- **Schriften:** nur Systemschriften (Handschrift-Stapel: Segoe Print, Bradley Hand, Chalkboard SE, Comic Sans MS).
- **Töne:** werden mit der Web Audio API erzeugt, es gibt keine Audiodateien.
- **Bimmelbahn:** läuft in einem abgeschotteten Bereich der Seite (Shadow DOM). So stören sich die Gestaltungen der beiden Spiele nicht. Die Bahn wird erst beim ersten Einsteigen gestartet und pausiert, solange der Zählrahmen offen ist.
- **Geräte:** Tablet, Smartboard, Smartphone und PC, bedienbar mit Finger und Maus. Die Bahn läuft auf dem Handy am besten quer.
- **Barrierearmut:** große Tippflächen, Tastaturfokus sichtbar, Animationen werden bei „Bewegung reduzieren“ abgeschaltet.

### Aufbau des Codes (Zählrahmen)

| Abschnitt im Skript | Aufgabe |
|---|---|
| `Katze Komma` | Zeichnung und Animationen der Katze |
| `Ton und Sprache` | Klickgeräusche, Fanfare, Vorlesen |
| `Bildteile` | Tiere, Eier, Hintergründe der Aufgabenbilder |
| `Zählrahmen` | Geometrie und Zeichnung für Drehen und Schieben |
| `Spielzustand` / `Aufgaben` | Ablauf von Zählen, Dazu und Weg |
| `Tippen, Wischen, Schieben` | Eingabe am Zählrahmen |
| `Fahrkarten` | Sterne, Fahrkarten, Mappe auf der Startseite |
| `Kommas Bimmelbahn` | Öffnen und Schließen der Bahn, Schnittstelle (Fahrkarten, Fahrtlänge, Vorlesen) |
| `Erwachsene: Bildkacheln` | Elternmenü |

Die Bimmelbahn steht im zweiten `<script>`-Block als Funktion `bootBimmel(ROOT, API)`.

---

## Lizenz

Kommas Zählrahmen & Kommas Bimmelbahn von Sebastian Wolf, lizenziert unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de). Du darfst die App teilen und bearbeiten, wenn du den Namen nennst und unter gleichen Bedingungen weitergibst.

## Impressum

Sebastian Wolf
Graf-Leopold-Ring 2
94099 Ruhstorf a.d.Rott
E-Mail: s.w.oer@outlook.de
