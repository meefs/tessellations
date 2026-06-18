# Interactive Tessellations

Generative tessellations turned into living, playable **single-file SVGs**. All the
motion is JavaScript embedded directly inside each `.svg` — no build step, no
dependencies.

**▶ Live:** https://meefs.github.io/tessellations/

## Pieces
- `tessellation-1.svg` — *Verdant* (~2 MB, smooth)
- `tessellation-2.svg` — *Ink* (~24 MB, heavier — slower to load)
- `index.html` — landing gallery

## Controls
| Input | Action |
|-------|--------|
| `Space` | cycle mode: Ocean · Swell · Repel · Attract · Vortex · Lens · Pick |
| `−` / `+` | power of the current mode |
| `[` / `]` | wave speed |
| `,` / `.` | influence radius |
| `C` | palette (25 colorways) |
| `M` | sound on/off |
| `G` | cursor glow on/off |
| `X` | clear picked tiles |
| `H` | hide the on-screen UI |
| mouse | distort / steer |
| click | ripple — or in **Lens**/**Pick**, magnify/highlight a tile |

## Run locally
Open any `.svg` in a browser (double-click, or drag it into a tab), or open `index.html`.

## A note on viewers
These need to be **the page being loaded** to run their script. Opened in a browser —
or served by GitHub Pages — they are fully interactive. GitHub's in-repo file preview,
`raw.githubusercontent.com` links, `<img>` embeds, and macOS Quick Look show them as a
**static image** (scripts are stripped for safety).
