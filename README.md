# astro-mascots

Public avatar assets for Moonfort's astro agents. Each image is served to Slack as a
per-message `icon_url` and uploaded as the global app icon (`apps.icon.set`).

- 7 characters, each with a base image plus 4 moods: `happy_idle`, `thinking_working`, `confused`, `sad_neglected`.
- Path: `<character>/<character>__<mood>.png`, 1254×1254 PNG.
- `manifest.csv` / `manifest.json` list the SHA-256 checksums.
- **Reference files by commit SHA, never by `main`.** The bytes at a URL must never change: a new image means a new commit.

| agent | character |
|---|---|
| astro (main) | 01_green_alien |
| astro-cpo | 04_yellow_fox |
| astro-ceo | 07_pink_axolotl |
| astro-cto | 03_blue_eyestalk_alien |
| astro-engineering | 06_teal_octopus |
| astro-god | 05_red_reptile |
| spare | 02_purple_cyclops |

Only images live here. No code, tokens or internal data.
