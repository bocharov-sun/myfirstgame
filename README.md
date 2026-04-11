# Stickfall Arena

Stickfall Arena is a browser ragdoll stickman arena with bots, falling weapons, achievements, classes, relics, cases, cosmetics, trades, boss fights, and a 100-floor tower mode.

The game is a static web project. It runs directly in the browser from `index.html`, so it can be published with GitHub Pages without a backend server.

## Play Locally

Open `index.html` in a browser.

## Controls

- `A` / `D` - move
- `W` - jump
- `E` - pick up weapon
- `Space` - attack or use weapon
- `Q` - drop weapon
- `F` - use relic
- `N` - change map
- `H` - achievements
- `Esc` - return to main menu

Controls can be changed in the in-game settings menu.

## Main Features

- Ragdoll stickman battles against bots
- Many weapon types with different attack visuals
- Random weapon drops with rarity timing
- Game modes: free-for-all, king of the hill, team battle, duel, octagram, and tower
- 100-floor tower mode with boss fights and save support
- Achievements and unlockable cosmetics
- Crafting, cases, relics, and trade codes
- Test map with a dummy and weapon selection
- Local browser saves through `localStorage`

## GitHub Pages

This project can be published from the repository root because `index.html` is at the top level.

Recommended GitHub Pages settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ root`

After GitHub Pages finishes deploying, the game should be available at:

`https://bocharov-sun.github.io/myfirstgame/`

## Notes

Progress is saved in the browser. A local file save and the GitHub Pages save are separate because browsers treat them as different origins.
