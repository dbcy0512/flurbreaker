# Flurbreaker

A local browser brick breaker about Flurb surviving asteroid space.

## Play

Open `index.html` directly, or run a local server:

```powershell
python -m http.server 5175
```

Then visit:

```text
http://localhost:5175
```

## Controls

- Move: WASD, currently A/D
- Launch: Space
- Pause: P
- Restart: R

## Features

- Zone 1: Space Navigation
- Levels 1-1 through 1-4 are data-defined brick breaker levels
- Level 1-5 is the first boss encounter: Driftmass Signal
- Level 1-1 is the tutorial: Driftstone Field
- Score, lives, combo counter
- Wide-paddle and extra-life powerups
- Particles and simple arcade polish
- Restrained neon accent pass for UI chrome, skimmer lights, Pulse Core, Driftstone seams, and powerups
- Animated three-pose pixel blob character in a dedicated Flurb Bay
- Mood-based Flurb palette and flux wisps in splash, bay, and pilot views
- Outer-space background with parallax star motion, nebula drift, route beacons, and distant exploration landmarks
- Skimmer replaces the plain paddle
- Pulse Core replaces the plain ball, with trail and impact feedback
- Typed particle effects for driftstone breaks and pulse impacts
- Driftmass boss has pulsing signal rings, shard connectors, damage cracks, and an exposed core phase
- Flurb is visible as the skimmer pilot during gameplay
- Flurb Bay appears as a before/between-stage interstitial for loop pacing and future ship evolution
- Pause screen also uses Flurb Bay so ship state remains visible
- Narrative start screen introducing Flurby as a mysterious Fluxmorph before gameplay begins

## Story Foundation

Flurb is traveling through the Space Navigation zone, learning to break routes through driftstone fields and survive the Driftmass Signal.

Flurby is a member of a species known as Fluxmorphs. The start screen frames her as a tiny traveler waking in unknown space while distant signals seem to remember shapes she has not become yet.

Flurb stays visible during play as the pilot. Flurb Bay appears between stages and during pause for ship presentation and later post-stage upgrade/evolution choices.

## Zone 1 Levels

- 1-1 Driftstone Field: gentle central mass for launch, steer, break, collect.
- 1-2 Broken Orbit: ring-like gaps for rebound and angle reading.
- 1-3 Dense Belt: thick asteroid belt with tougher driftstone pressure.
- 1-4 Approach Vector: chevron route that points toward the future boss signal.
- 1-5 Driftmass Signal: 4 outer driftstone shards at 3 HP each, then an 8 HP exposed core.

Levels 1-4 in each zone are intended to use map layouts as part of the aesthetic language. In Space Navigation, maps should feel like asteroid routes, broken orbits, dense belts, and approach vectors rather than generic brick walls.

## Materials

- Zone 1 breaker levels use Driftstone, a space-worn material with mineral seams and chipped stone surfaces.

## Effects Foundation

- Brick breaks can emit material-specific debris, such as driftstone chips and mineral sparks.
- Pulse Core hits emit short impact rings and directional sparks.

## Boss Foundation

- Boss pieces are separate hit targets rather than normal bricks.
- Driftmass outer pieces drop away incrementally when destroyed.
- The boss core is locked until all outer pieces are destroyed.
- Driftmass core clear currently clears Zone 1.
