# Three Games

One page for three browser games. Switch with the arrow keys, the on-screen
arrows, the dots, or a swipe; Play opens the game.

| Game | Plays at |
| --- | --- |
| Astral Clash | https://astral-clash.vercel.app/ |
| The Corridor | https://the--corridor.vercel.app/ |
| Pulse Arena | https://pulse-arena-0.vercel.app/ (also on [itch.io](https://arjungali-hub.itch.io/pulse-arena)) |

A game can be linked to directly: `#astral-clash`, `#the-corridor`, `#pulse-arena`.

Static, no build step: `index.html` holds the markup, styles and script.

- `img/astral-clash.webp` is Astral Clash's loading tableau.
- The Corridor's map and Pulse Arena's arena are drawn in the page (canvas and SVG),
  so they need no image.
- `fonts/astral-title.woff2` is Saira, under the SIL Open Font License (`fonts/OFL-Saira.txt`).

To add a game: copy a `<section class="slide">`, give it an `id`, a background and
copy, add a dot for it, and update the "of 3" labels.
