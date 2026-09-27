# Ice Tag

A browser-based multiplayer Ice Tag game for up to eight players. It uses the supplied board artwork and implements random start positions, a four-result spinner, one-step movement, obstacle avoidance, tagging, automatic turn advancement, and last-player-standing victory.

## Run locally

Open `index.html` in a browser. For a reliable local server, run `python3 -m http.server` in this directory and visit `http://localhost:8000`.

## GitHub Pages

1. Open repository **Settings → Pages**.
2. Set the source to **Deploy from a branch**.
3. Select `main` and `/ (root)`, then save.
4. Open the generated Pages URL.

## Included files

- `index.html` — game interface.
- `styles.css` — responsive styling and token visuals.
- `game.js` — game state, spinner, movement, obstacles, tagging, and win logic.
- `board.jpg` — supplied game board artwork.
