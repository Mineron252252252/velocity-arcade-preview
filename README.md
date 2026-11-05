# VELOCITY — arcade racing menu

Adaptive full-screen browser prototype for a racing arcade cabinet.

## Preview

Open `index.html` in a modern Chromium-based browser. The layout adapts to the window size; use F11 for a full-screen preview.

## Controls

- Left and right arrow keys: switch games.
- Mouse: select a side card or drag the carousel.
- Enter or the **ИГРАТЬ** button: show the launch placeholder.

## Games

The four menu entries and their artwork are configured in `app.js`. Project CARS uses the cropped, optimized cover `assets/project-cars-card.jpg`; the other car illustrations are inline SVG. The prototype needs no network access.

## Project files

- `index.html` — interface structure.
- `styles.css` — responsive layout, visual styling, and motion.
- `app.js` — game data, carousel positioning, and input handling.

This is a front-end prototype. The launch button is a placeholder until the Windows game-launch integration is defined.
