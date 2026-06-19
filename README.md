# wm.github.io

Project page for a solo reproduction of two world-model frameworks across four environments:

- **DreamerV3** (JAX) — Minecraft (Diamond) and ProcGen CoinRun
- **LeWM** (JEPA-based world model) — Cube manipulation and PushT

The page (`index.html`) is a single static file — open it directly or serve it with any static
server (e.g. `python -m http.server`).

## Media status

| Task | Status | Files |
|------|--------|-------|
| LeWM · Cube   | ✅ wired | `static/videos/cube/dataset_groundtruth.gif`, `learned_epoch19.gif` |
| LeWM · PushT  | ✅ wired | `static/videos/pusht/progression_epochs.gif`, `grid_scenarios.gif` |
| DreamerV3 · Minecraft | ⏳ placeholder | drop clips in `static/videos/minecraft/` |
| DreamerV3 · CoinRun   | ⏳ placeholder | drop clips in `static/videos/coinrun/` |

For the placeholder tasks, drop a `.mp4` (or `.gif`) at the path printed under each slot in the
page, then swap the `<div class="media-placeholder">…</div>` for a
`<video autoplay muted loop playsinline></video>` (or `<img>`) pointing at it.

## TODO before publishing

- Fill in your affiliation / resume link in the hero (`<!-- TODO -->` markers in `index.html`).
- Point the "LeWM Code" GitHub button at the real repo URL.
- Render and drop in the Minecraft / CoinRun epoch clips.

## Template credit

Built on the [Nerfies](https://github.com/nerfies/nerfies.github.io) project page template,
licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
