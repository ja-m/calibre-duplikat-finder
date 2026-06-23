# 🗄️ Calibre Duplikat-Finder

**Findet doppelte Bücher in deiner Calibre-Bibliothek — direkt im Browser, ohne Installation.**

🔗 **[→ App öffnen](https://ja-m.github.io/calibre-duplikat-finder/)**

---

## Was macht das Tool?

Du hast eine große Calibre-Bibliothek und willst wissen, ob Bücher mehrfach vorhanden sind? Dieses Tool liest deine `metadata.db` direkt im Browser aus und zeigt dir alle Duplikate gruppiert an — nach Titel und Autor.

## So funktioniert es

1. `metadata.db` aus deinem Calibre-Bibliotheksordner öffnen  
   *(Standard: `~/Calibre Library/metadata.db`)*
2. Datei in die Web-App ziehen oder per Klick auswählen
3. Duplikate werden sofort angezeigt — gefiltert nach Titel + Autor
4. Optional: Ergebnisse als CSV exportieren

## Features

- **Keine Installation** – läuft als einzelne HTML-Datei im Browser
- **Kein Upload** – deine Daten verlassen nie deinen Computer
- **Suchfilter** – Duplikate nach Titel oder Autor durchsuchen
- **CSV-Export** – alle Duplikate für die Weiterverarbeitung exportieren
- **Statistiken** – Übersicht über Gesamtanzahl, Duplikat-Gruppen und betroffene Einträge

## Datenschutz

Die App verwendet [SQL.js](https://github.com/sql-js/sql.js/), um SQLite-Datenbanken direkt im Browser zu lesen. Es werden **keine Daten an einen Server gesendet**. Die gesamte Verarbeitung findet lokal auf deinem Gerät statt.

## Technologie

- Vanilla HTML/CSS/JS
- [SQL.js](https://github.com/sql-js/sql.js/) (SQLite im Browser via WebAssembly)

## Lizenz

MIT
