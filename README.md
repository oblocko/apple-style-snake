# Snake Arcade

A Snake game in a single HTML file, with an iOS-style interface built around a Dynamic Island HUD.

**Play:** https://oblocko.github.io/apple-style-snake/

## Features

- Rounded "squircle" snake on a 15 × 15 board, with smooth movement between cells
- Three modes: **Classic**, **Wrap** (walls let you through to the other side) and **Blocks** (fixed obstacles)
- Three speeds: **Easy**, **Normal** and **Hard**, each with its own best score
- Share your score from the result card (share sheet on phones, copied to the clipboard on desktop)
- Dynamic Island HUD: live score and best score, tap to pause, and it expands into the result card
- On an iPhone with a Dynamic Island, opened from the home screen, the HUD sits on the real island
- Light and dark themes (Auto follows the system), six snake colors, optional sound effects
- Best scores, mode, speed, color and theme saved in the browser
- Works with keyboard, swipe, or the on-screen direction pad
- Can be added to the home screen as an app

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys or W A S D | Swipe, or the direction pad |
| Pause / resume | Space | Tap the Island |
| Restart | R | Play Again |
| Back to menu | Esc | Menu |

## Add to your home screen

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, open the menu, then **Add to Home screen**.

If you added it before, remove the old icon first so the latest version and icon are used.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole game: markup, styles and script |
| `manifest.webmanifest`, `icons/` | Home screen name and icons |
| `apple-style-snake.html` | Redirects old links to the game |

Snake Arcade is an independent fan project. It is not made by, affiliated with, or endorsed by Apple Inc.
