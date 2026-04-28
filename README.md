# Inforcer Nordic Run

A Temple Run-style endless runner game where you escape Santa Claus through the Nordic wilderness.

**[Play it now](https://timothyoelkers-cloud.github.io/inforcer-nordic-run/)** (once GitHub Pages is enabled)

## Features

- **3 Playable Characters** — King Gower (balanced), Silly Sailor Sam (fast), and Viking Larsen (tough)
- **Santa Claus chase mechanic** — keep your distance or get caught!
- **4 Power-ups** — Shield, Magnet, Speed Boost, Double Coins
- **4 Environment Zones** — Snowy Forest, Ice Cave, Fjord Coast, Aurora Peak
- **Synthesized Nordic music & sound effects** (Web Audio API, no external files)
- **Persistent leaderboard** with top 5 runs
- **Coin shop** with consumable boosts and character skins
- **Combo counter, distance tracker, pause/resume**

## Controls

| Action | Key |
|--------|-----|
| Move left/right | Arrow Keys / A,D |
| Jump | Space / Up Arrow / W |
| Slide | Down Arrow / S |
| Pause | P / Escape |
| Mute | Click the music note in the HUD |

Touch / swipe controls supported on mobile.

## How to Run

Just open `index.html` in any modern browser — it's a single self-contained file with no build step or dependencies.

## Tech

- Vanilla JavaScript + HTML5 Canvas
- Web Audio API for synthesized music and sound
- LocalStorage for persistent wallet, leaderboard, and unlocks
- No external dependencies
