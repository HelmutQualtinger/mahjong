# 雀 Mahjong Solitaire

A classic Mahjong solitaire game playable directly in the browser — no dependencies, no build step, single HTML file.

<img src="screenshot.png" align="right" width="340" alt="Mahjong Screenshot"/>

## How to Play

1. Open `mahjong.html` in any modern browser
2. Select a **Layout** from the dropdown and click **↺ Neu** to start
3. Click two matching free tiles to remove them as a pair
4. A tile is *free* if nothing is stacked on top of it and at least one side (left or right) is open
5. Clear all 144 tiles to win

## Features

- **5 selectable layouts** — Schildkröte, Drache, Pyramide, Kreuz, Festung
- 144 tiles across up to 6 stacked layers
- Full Unicode Mahjong tile set: Characters, Bamboo, Circles, Winds (東南西北), Dragons (中發白), Flowers & Seasons
- Color-coded suits with corner rank labels
- Visual 3-D tile effect (raised edges, depth shadows)
- Undo last move, Hint (flashes a valid pair), Timer, Score
- Win / no-moves detection with overlay
- Purely client-side — works offline, no server needed

## Layouts

| Layout | Shape | Layers |
|---|---|---|
| 🐢 Schildkröte | Classic pyramid with side wings | 6 |
| 🐉 Drache | Long horizontal dragon: spine, belly, head & tail | 6 |
| 🔺 Pyramide | Concentric shrinking rectangles | 4 |
| ✚ Kreuz | Plus/cross shape with stacked center | 4 |
| 🏰 Festung | Concentric rectangle rings (castle seen from above) | 4 |

## Run Locally

```bash
open mahjong.html        # macOS
xdg-open mahjong.html   # Linux
start mahjong.html       # Windows
```

---

## Deutsch

Klassisches Mahjong-Solitaire, direkt im Browser spielbar — keine Abhängigkeiten, kein Build-Schritt, eine einzige HTML-Datei.

### Spielanleitung

1. `mahjong.html` in einem modernen Browser öffnen
2. Layout im Dropdown wählen und **↺ Neu** klicken
3. Zwei übereinstimmende freie Steine anklicken, um sie als Paar zu entfernen
4. Ein Stein ist *frei*, wenn er nicht von einem anderen Stein bedeckt ist und mindestens eine offene Seite (links oder rechts) hat
5. Alle 144 Steine abräumen, um zu gewinnen

### Funktionen

- **5 wählbare Layouts** — Schildkröte, Drache, Pyramide, Kreuz, Festung
- 144 Steine auf bis zu 6 gestapelten Ebenen
- Vollständiger Unicode-Steinsatz: Schriftzeichen, Bambus, Kreise, Winde, Drachen, Blumen & Jahreszeiten
- Zug rückgängig machen, Hinweis-Funktion, Timer, Punktestand
- Sieg- und Keine-Züge-Erkennung
- Rein clientseitig — funktioniert offline
