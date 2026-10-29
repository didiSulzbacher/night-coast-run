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
- Three gangs split the city: the Neon Serpents, the Iron Crowns and the Dock Rats. Each has its own turf, members, cars and a respect meter. Hurt a gang and its respect drops (its rival likes that); drop low enough and its members shoot on sight.
- **Story mode:** gang phones ring in the gang's colour and offer jobs against its rival: wreck a rival car, wipe out a rival crew, steal a rival car for the gang garage, or run a package. After four jobs a gang offers its big job, taking out the rival boss and their bodyguards, which puts that gang out of business. Two big jobs and the city is yours. Progress, cash and weapons are saved. **Free roam** is a fresh city every time.

| Action | Keys |
|---|---|
| Walk / drive and steer | Arrow keys or WASD |
| Get in or out of a car | E or Enter |
| Fire (on foot) | F, Ctrl or Space |
| Handbrake (in a car) | Space |
| Switch weapon | Q or Tab |
| Pause / mute | P or Esc / M |

On touch screens, on-screen buttons appear automatically. Best cash and jobs done are saved in local storage.

# Texas Hold'em

`games/texas-holdem/` is a no-limit Texas Hold'em sit-and-go tournament in a single HTML file.

- Play heads-up, 4-handed or 6-handed against AI players. Everyone starts with 1,500 chips, the blinds go up every 8 hands, and the last player with chips wins.
- Full rules: dealer button, blinds, minimum raises, all-ins, side pots and split pots. The best five-card hand is highlighted at showdown.
- Each AI player has its own style (tight or loose, passive or aggressive, how often it bluffs). They decide by simulating run-outs to estimate their chance of winning, then weighing that against the pot odds.
- Optional "Odds" readout shows your own chance of winning the hand. "Fast" speeds up the other players.
- Keys: F fold, C or Space check / call, R raise, A all-in, arrow keys to size the raise.

# Neon Breakout

`games/neon-breakout/` is a brick breaker in a single HTML file.

- 15 levels, with a boss fight every fifth level: the Warden, the Hydra and the Overmind. Bosses move, shoot at your paddle (a hit stuns it for a moment) and the Overmind summons new bricks. After level 15 the levels loop, faster.
- Bricks: plain, tough (2 hits), hard (3 hits), steel (unbreakable), explosive (takes out its neighbours) and power-up bricks.
- Power-ups: multi-ball, wide paddle, lasers, slow ball, catch, fireball, extra life, and a narrow paddle to avoid. Breaking bricks without touching the paddle builds a combo multiplier up to x5.
- Level editor: paint your own level, play-test it, and share it as a level code (`NB1:...`) that anyone can load.
- Controls: mouse, touch or arrow keys to move, click, tap or Space to launch, P to pause. High score and unlocked levels are saved in the browser.

# Star Swarm

`games/star-swarm/` is a vertical shoot-'em-up in a single HTML file.

- Three sectors of enemy waves (drones, fighters, kamikazes, turrets, spinners and cruiser mini-bosses), each ending in a bullet-hell boss with three phases: the Hive Queen, the Dreadnought and the Core. After sector 3 the game loops, harder.
- Your guns fire on their own. Power-ups upgrade them to five levels, add up to three homing missiles, give you a shield or an extra bomb. Bombs clear the screen of bullets and turn them into medals.
- Killing enemies in quick succession builds a chain multiplier up to x8, and medals are worth more while it lasts.
- Easy, Normal and Hard difficulty.
- Controls: mouse, or drag anywhere on a touch screen (your finger can stay below the ship), or the arrow keys with Shift to move slowly. X, B, Space, right-click or the BOMB button for bombs, P to pause. The high score is saved in the browser.

# Tank Duel

`games/tank-duel/` is a top-down tank battle in a single HTML file.

- Play against 1 to 3 computer tanks, or with 2 players on one keyboard (plus up to 2 computer tanks). Rounds go to the last tank standing, and a match is first to 3, 5 or 7 round wins.
- Every round gets a new symmetric map: steel walls that shells bounce off, brick walls that break after two hits, and bushes to hide in.
- Power-ups: rapid fire, triple shot, explosive shells (they blast through brick), shield, speed and repair. Each tank takes three hits.
- Computer tanks come in Rookie, Veteran and Ace. They find paths through the maze, shoot their way through brick, look for bank shots off steel walls and dodge incoming shells.
- Controls: player 1 drives with W A S D and fires with Space or F. Player 2 drives with the arrow keys and fires with Enter or /. On touch screens there's a joystick and a fire button. P pauses. On a tall phone screen the arena turns portrait.

# Turbo Cup

`games/turbo-cup/` is a top-down racer in the style of Micro Machines, in a single HTML file. It uses the same car handling as Gridlock City.

- Four tracks: Harbor Loop, Canyon Run, Snow Ridge (slippery) and Neon Nights. Each race is three laps against five rivals.
- Championship: race all four tracks for points (10, 8, 6, 5, 4, 3) with standings after every race. Or pick any track for a quick race.
- Four cars to choose from (Furore GT, Stallion, Zippy, Cosmo) and three rival levels. Rivals brake for corners, swing wide into them, pull out to overtake and recover from crashes.
- Grass slows you down and tyre walls bounce you back. Cutting across the infield doesn't count as progress.
- Controls: arrow keys or W A S D, Space to handbrake and drift, P to pause. On touch screens there are on-screen buttons. Lap records and cups won are saved in the browser.
