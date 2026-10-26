# Arcade

A small collection of browser games. No build step, no dependencies: open `index.html` in a browser and pick a game from the home screen.

## Adding a game
Put it in `games/<id>/index.html`, then add an entry to the `GAMES` list in the root `index.html` (title, blurb and a CSS class that draws its card picture). Link back to the home screen with `href="../../"`.

# Night Coast Run

`games/night-coast-run/` — a retro pseudo-3D driving game in a single HTML file.

## Modes
Endless run (with an oncoming lane and police roadblocks the longer you survive), head-on rush (survive waves of oncoming traffic and roadblocks), time trial, rival race, slalom jump, big jump, bullseye jump, stunt show, demolition derby, getaway and hot pursuit.

## Features
- 7 vehicles with their own stats and abilities, plus garage upgrades bought with coins
- Power-ups, police chases, car damage and repair kits
- Side missions that pay out coins
- Weather: clear, rain, fog, snow or random

## Controls
| Action | Keys |
|---|---|
| Drive | Arrow keys or WASD |
| Drift | Tap brake or Ctrl while steering |
| Jump | Space or J |
| Nitro | Shift or N |
| Fire | F |
| Pause | P or Esc |

On touch screens, on-screen buttons appear automatically.

## Play online
Enable GitHub Pages (Settings, Pages, deploy from the `main` branch) and the home screen is served from `index.html`.

Progress, records and coins are saved in the browser's local storage.
