# Workwear Bestellprozess-Timeline

Interaktive, animierte Timeline des Beschaffungsprozesses für Arbeitskleidung (Pöppel Workwear Management). Sie stellt Station für Station gegenüber, was ein Bestellvorgang **heute** kostet und was das System davon **übernimmt**.

**Live:** https://svenn8n-a11y.github.io/Workwear-Timeline/

## Funktionen

- **Drei umschaltbare Prozesse** (Button oben):
  - *Mitarbeiter meldet* — der klassische Ablauf (bottom-up)
  - *Zentral über Einkauf* — top-down, zentrale Bestellrunde
  - *Mit Personaldienstleistern* — Zeitarbeit/Projektspitzen (eigener Katalog, Größen-Umschlüsselung, Abrechnungsmodelle, Haftung)
- **Prinzip je Station:** oben der Ist-Zustand (heute), unten die Pöppel-Lösung
- **Meterstab-Achse** mit feinen und großen Strichen, in der jeweiligen Stationsfarbe
- **Zeit-Panel rechts:** geschätzter Aufwand je Schritt (inkl. Wartezeit), kumulierter Counter, besondere Lieferzeiten (z. B. Veredelung „+ 3–6 Wochen")
- **Pöppel-Zeit unten:** der Sekunden-Kontrast zur Heute-Zeit
- **Involvierte Personen links** als Avatare in der Stationsfarbe (Regenbogen über die Stationen)
- **Fokus-Box** mit transparenter Gradient-Outline um die aktive Station
- **„entfällt"-Eckband** bei Schritten, deren manueller Aufwand mit Pöppel wegfällt
- **Hell/Dunkel-Umschalter** (Button oben rechts, Auswahl wird gespeichert)
- **Mobil:** vertikale Liste zum normalen Scrollen (kein Scroll-Jacking unter 820 px)

## Technik

- Selbstenthaltene Einzeldatei: `index.html` — kein externer Code, keine Abhängigkeiten, offline lauffähig
- Datengetrieben: Prozesse und Stationen liegen als Arrays im Script; neue Stationen/Prozesse sind dort leicht zu ergänzen (Nummerierung erfolgt automatisch)

Interner Konzept-Prototyp · Juli 2026
