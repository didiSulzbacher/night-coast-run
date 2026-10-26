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

# Gridlock City

`games/gridlock-city/` is a top-down city crime game in the style of GTA 2, in a single HTML file.

- A city of streets, parks, parking lots and alleys, with buildings drawn in fake 3D like GTA 2. The camera zooms out as you speed up.
- Walk around, carjack any car (7 types with drift handling) and pick up a pistol, machine gun or rocket launcher.
- Wanted level of 1 to 5 stars. Cops chase and ram you, get out to arrest you, and shoot from 3 stars. Drive onto a pink SPRAY pad to clear your stars and repair the car.
- Answer ringing phone booths for jobs: courier runs, car orders, hits, taxi fares, getaways and demolition.

| Action | Keys |
|---|---|
| Walk / drive and steer | Arrow keys or WASD |
| Get in or out of a car | E or Enter |
| Fire (on foot) | F, Ctrl or Space |
| Handbrake (in a car) | Space |
| Switch weapon | Q or Tab |
| Pause / mute | P or Esc / M |

On touch screens, on-screen buttons appear automatically. Best cash and jobs done are saved in local storage.
