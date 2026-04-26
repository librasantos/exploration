# Explore Quest 🗺️✨

A multi-world exploration adventure built for kids. Travel through 5 elemental worlds — Pyros, Aqualon, Glacius, Verdania, Mekanos — plus a Mirror Realm bonus level. Each world has unique mechanics, missions, and gem-collection challenges.

## Worlds

- **Pyros** 🔥 — Fire/desert world
- **Aqualon** 🌊 — Ocean world
- **Glacius** ❄️ — Ice world
- **Verdania** 🌳 — Forest world
- **Mekanos** ⚙️ — Mechanical world
- **Mirror Realm** 🪞 — Bonus level with a mirror twin and reflective puzzles

## Features

- 6 distinct worlds with themed biomes
- Mission-based progression with pass/fail screens
- Gem collection (gold, glowing, animated)
- Difficulty scaling per level
- Multi-touch controls (move + jump + interact simultaneously)
- HQ menu with scrollable level grid

## Controls

- **Joystick (bottom-left)** — Move
- **Action buttons (right)** — Jump, interact
- Touch-optimized for iPhone Safari

## Tech

Single-file HTML game using [Phaser 3.80.1](https://phaser.io). No build step.

## Deploy

### Vercel
Drop this folder into Vercel — it auto-detects as a static site. Or:
```bash
vercel --prod
```

### GitHub Pages
Push to a GitHub repo, then in repo Settings → Pages, set source to `main` branch root. The game will be live at `https://YOUR-USERNAME.github.io/explore-quest/`.

### Local
Open `index.html` directly in a browser, or serve with any static server:
```bash
python3 -m http.server 8000
```
