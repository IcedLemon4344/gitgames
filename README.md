# GitGames

A browser-based retro arcade featuring a searchable game library, favorites, a hidden secret mission, and a bonus game unlocked with a randomly generated promo code.

## Features

- Searchable arcade library
- Category filters and favorites
- Neon Vault hidden-key mission
- Random promo code for each browser session
- Hidden **Neon Defender** bonus game
- Local high-score and favorites storage
- Responsive layout for desktop and mobile

## Play

Open `index.html` in a browser or serve the repository with a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Unlock Neon Defender

1. Open the **SECRET MISSION: FIND THE HIDDEN KEY** section.
2. Click the objects in the Neon Vault until you find the hidden key.
3. Copy the randomly generated promo code that appears.
4. Enter it in the Retro Promo Code Terminal and select **UNLOCK**.
5. Neon Defender will appear in the game library.

The unlock state and promo code are stored locally in your browser. Clearing browser local storage resets the unlock state and generates a new promo code.

## Controls

- **Left / Right or A / D:** Move
- **Up or W:** Move, jump, or thrust in supported games
- **Space:** Fire or jump
- **Escape:** Close the game window

## Technologies

- HTML
- CSS
- Vanilla JavaScript
- Canvas API
- Browser `localStorage`
