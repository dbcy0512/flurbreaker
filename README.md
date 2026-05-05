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
- Level 1-5 is reserved for a future boss encounter
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
- Flurb is visible as the skimmer pilot during gameplay
- Flurb Bay appears as a before/between-stage interstitial for resources and future ship evolution
- Pause screen also uses Flurb Bay so resources and ship state remain visible
- Real start screen introducing Flurb as a Fluxmorph before gameplay begins

## Story Foundation

Flurb is traveling through the Space Navigation zone. Water, iron, and platinum are critical to survival, and can be collected from falling asteroids.

Flurb is a member of a species known as Fluxmorphs. The start screen only hints at identification for now, leaving room for the character and lore to evolve later.

Flurb stays visible during play as the pilot. Flurb Bay appears between stages and during pause for resources, ship presentation, and later post-stage upgrade/evolution choices.

## Zone 1 Levels

- 1-1 Driftstone Field: tutorial for launch, steer, break, collect.
- 1-2 Broken Orbit: rebound gaps and angle reading.
- 1-3 Dense Belt: tougher driftstone and resource pressure.
- 1-4 Approach Vector: prepares for the future boss route.
- 1-5 Driftmass Signal: boss placeholder, not implemented yet.

## Resource Evolution Roles

- Water: Flurb stability and recovery capacity.
- Iron: skimmer hull, impact tolerance, and structure.
- Platinum: Pulse Core focus, signal range, and advanced systems.

## Materials

- Zone 1 breaker levels use Driftstone, a space-worn material with mineral seams and chipped stone surfaces.
