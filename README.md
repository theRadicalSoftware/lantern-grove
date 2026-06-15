# Lantern Grove

Lantern Grove is a cozy single-file browser adventure built with Three.js. You play as Sprout, explore a small village, meet animal villagers, grow sparkle flowers, catch fireflies, and restore the Lantern Tree.

## Play Locally

From the project directory:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/lantern-grove.html
```

The game is implemented in `lantern-grove.html` and loads Three.js from a CDN, so an internet connection is needed the first time the page loads.

## Controls

- Move: `WASD` or arrow keys
- Interact: `E` or space
- Touch devices: use the on-screen joystick and action button

## Current Features

- Explorable low-poly village with paths, houses, shop, garden, pond, town hall, and graveyard.
- Seven villagers, including Sofia the Hen and Elder Moss.
- Inventory, pickups, Rocco's trading post, and simple quest progression.
- Planting and watering garden plots to grow sparkle flowers.
- Fireflies that appear at night.
- In-game world clock with a seven-day week, day rollover, and time-based lighting.
- Dynamic day, evening, and night atmosphere with stars, moon, window glow, and firefly behavior.

## Project Structure

```text
lantern-grove.html  # Complete game, UI, styles, and Three.js scene
README.md           # Project overview and local run instructions
```

## Development Notes

This is intentionally a small static project. There is no bundler, package manager, or build pipeline required right now. Keep changes scoped to `lantern-grove.html` unless the project grows enough to justify splitting assets or modules out into separate files.
