# Unit 8 Review: Exam Prep

| Page | File | Address |
|---|---|---|
| Landing page | `index.html` | `https://USERNAME.github.io/g10/unit8/` |
| X-Pedition (review game) | `xpedition/index.html` | `https://USERNAME.github.io/g10/unit8/xpedition/` |

X-Pedition is a retro platformer that reviews the course one world at a time. World 1 (Balance Meadows) covers Unit 1, and World 2 (Factor Forest) covers Unit 2. Each world has five levels, and the fifth is a boss level. New worlds will be added to `xpedition/index.html` as they are built.

## Adding or updating this unit

1. Drag the `unit8` folder into the `g10` repository and commit.
2. To update the game later, replace only `unit8/xpedition/index.html`.
3. Add a row for Unit 8 to the root README's unit table.

## Fonts

The pages use Press Start 2P, Atkinson Hyperlegible (400 and 700) and Kalam (700). These are the same fonts Unit 2 uses, with the same Fontsource file names:

- `press-start-2p-latin-400-normal.woff`
- `atkinson-hyperlegible-latin-400-normal.woff`
- `atkinson-hyperlegible-latin-700-normal.woff`
- `kalam-latin-700-normal.woff`

Each `@font-face` rule looks in `unit8/fonts/` first and then in `unit2/fonts/`, so the pages show the right fonts as soon as they are on the site. To make `unit8` self-contained, copy those four files from `unit2/fonts/` into `unit8/fonts/`, and copy the matching licence files from `unit2/fonts/licenses/` into `unit8/fonts/licenses/`. All three font families are under the SIL Open Font License.

## Privacy

- Nothing typed on these pages is sent anywhere, and the pages load nothing from other websites.
- The game saves its progress (stars, total score, and a mid-level resume point) in this browser's localStorage under `xped-progress-v1`, and its sound settings under `xped-settings`.
- Save codes are made and checked on screen. A save code holds stars and the total score only, with no names.
