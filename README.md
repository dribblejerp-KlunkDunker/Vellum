# Vellum

[![Launch Vellum](https://img.shields.io/badge/Launch_Vellum-Open_Web_App-c83e2b?style=for-the-badge)](https://dribblejerp-klunkdunker.github.io/Vellum/)

**World Atlas & Floor Plan Studio** — turn written lore into readable 2D architectural floor plans, live 3D isometric views, and interactive GM/playtest sessions with zero build steps.

*(To enable the live link above, go to **Settings → Pages** in this repository and set Source to **Deploy from a branch (`main`)**.)*

---

## Features

- **Lore-to-Layout Parser**: Paste markdown or bulleted zone lists to auto-generate a numbered floor plan, zone key, and held-heart chamber.
- **2D SVG Architect's Renderer**: Crisp 1000 px sheets with hatch/pattern fills (`rock`, `ash`, `water`, `grass`, `snow`, `cinder`, `reed`, `spore`, `deck`, `iron`, `ice`), scale bar, north arrow, animated shortcut routes, and an auto-built legend.
- **Live 3D Isometric View**: Real-time 3D extrusion of rooms, tunnels, staircases, bridges, and held-heart chambers across multiple floors.
- **Drag-and-Drop Editor**: Place and reposition rooms, tunnels, staircases, bridges, and markers with snap-to-grid, undo/redo, and JSON export.
- **GM & Playtest Dock**:
  - **Fog of War** (click rooms to uncover)
  - **Interactive Range Finder** (`Shift + Drag` for distance in meters)
  - **Line of Sight (LOS)** raycasting between tokens
  - **Turn Order & Round Tracker**
  - **Dice Roller** with modifiers (`1d20+4`)
  - **Combat Log / Event Ticker**, **Quick GM Notes**, and **Inventory**
- **Genre-Agnostic Themes**: Switch between **Ash Paper** (fantasy/dungeon) and **Horror Station** (sci-fi/derelict) out of the box.

---

## Screenshots & Demos

### Live Workflow Demo
![Vellum Workflow Demo](docs/shots/vellum_demo.gif)

### Multi-Floor 3D Dungeon (3 Floors, Bridges & Held Heart)
![Multi-Floor 3D Dungeon](docs/shots/multi_floor_3d_dungeon.gif)

### Full Studio (`app.html`)
![Vellum Studio](docs/shots/final_app.png)

### Ash Paper Theme
![Ash Paper Theme](docs/shots/theme_ash_paper.png)

### GM Playtest Dock & Line of Sight (`gm_preview.html`)
![GM Playtest Dock](docs/shots/gm_preview.png)

### 2D Drag-and-Drop + Live 3D Isometric View (`dungeon_3d_preview.html`)
![2D and 3D Dungeon View](docs/shots/dungeon_3d_preview.png)

---

## Quick Start

1. Open `app.html` directly in Chrome, Firefox, or Edge — no build step required.
2. Or run a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000/app.html`.
