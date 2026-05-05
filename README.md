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

- 3 data-defined stages to start
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
- Dedicated Flurb Bay in the side panel for resources and future post-stage ship evolution
- Real start screen introducing Flurb as a Fluxmorph before gameplay begins

## Story Foundation

Flurb is traveling through space. Water, iron, and platinum are critical to survival, and can be collected from falling asteroids.

Flurb is a member of a species known as Fluxmorphs. The start screen only hints at identification for now, leaving room for the character and lore to evolve later.

Flurb stays visible during play as the pilot. The side-panel bay is reserved for resources, ship presentation, and later post-stage upgrade/evolution choices.
