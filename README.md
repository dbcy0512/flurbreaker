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
- Animated three-pose pixel blob character in a dedicated Flurb Bay
- Flurb resource HUD for water, iron, and platinum
- Falling asteroids that pass through bricks and can be collected by the player
- Outer-space background with parallax star motion
- Resource Skimmer replaces the plain paddle
- Pulse Core replaces the plain ball, with trail and impact feedback
- Typed particle effects for driftstone breaks, resource pickups, and pulse impacts
- Flurb is visible as the skimmer pilot during gameplay
- Flurb Bay appears as a before/between-stage interstitial for resources and future ship evolution
- Pause screen also uses Flurb Bay so resources and ship state remain visible
- Real start screen introducing Flurb as a Fluxmorph before gameplay begins

## Story Foundation

Flurb is traveling through the Space Navigation zone. Water, iron, and platinum are critical to survival, and can be collected from falling asteroids.

Flurb is a member of a species known as Fluxmorphs. The start screen only hints at identification for now, leaving room for the character and lore to evolve later.

Flurb stays visible during play as the pilot. Flurb Bay appears between stages and during pause for resources, ship presentation, and later post-stage upgrade/evolution choices.

## Zone 1 Levels

- 1-1 Driftstone Field: gentle central mass for launch, steer, break, collect.
- 1-2 Broken Orbit: ring-like gaps for rebound and angle reading.
- 1-3 Dense Belt: thick asteroid belt with tougher driftstone/resource pressure.
- 1-4 Approach Vector: chevron route that points toward the future boss signal.
- 1-5 Driftmass Signal: 4 outer driftstone shards at 4 HP each, then an 8 HP exposed core.

Levels 1-4 in each zone are intended to use map layouts as part of the aesthetic language. In Space Navigation, maps should feel like asteroid routes, broken orbits, dense belts, and approach vectors rather than generic brick walls.

## Resource Evolution Roles

- Water: Flurb stability and recovery capacity.
- Iron: skimmer hull, impact tolerance, and structure.
- Platinum: Pulse Core focus, signal range, and advanced systems.

## Materials

- Zone 1 breaker levels use Driftstone, a space-worn material with mineral seams and chipped stone surfaces.

## Effects Foundation

- Brick breaks can emit material-specific debris, such as driftstone chips and mineral sparks.
- Resource pickups emit colored motes matching the collected resource.
- Pulse Core hits emit short impact rings and directional sparks.

## Boss Foundation

- Boss pieces are separate hit targets rather than normal bricks.
- Driftmass outer pieces drop away incrementally when destroyed.
- The boss core is locked until all outer pieces are destroyed.
- Driftmass core clear currently grants a small iron/platinum bonus and clears Zone 1.
