# Gogogaga

Gogogaga is a self-contained local two-player platform fighter. Battle on a wide, multi-platform stage, build damage to increase knockback, use one double jump per airtime, and try to knock your opponent past the blast zones. The camera follows both fighters and smoothly zooms to keep them in view.

## Run the game

Open `index.html` directly in a modern browser, or serve the repository root with any static file server. There is no build step, package installation, or external dependency. The page is also configured for static hosting on GitHub Pages.

## Controls

| Action | Player 1 | Player 2 |
| --- | --- | --- |
| Move left / right | `A` / `D` | `←` / `→` |
| Jump / double jump | `W` | `↑` |
| Drop through a one-way platform | `S` | `↓` |
| Attack | `F` | `/` (Slash) |
| Rematch (after a win) | `R` | `R` |

## Roadmap

- **Phase 2 — Sprite system:** Add a reusable character animation and sprite pipeline while preserving the procedural stick-figure fallback.
- **Phase 3 — Menus:** Add title, character selection, settings, and pause menus.
- **Phase 4 — Online multiplayer:** Add networked matches with synchronized game state and matchmaking.
