# wm.github.io

Project page for a solo reproduction of two world-model frameworks across four environments:

- **DreamerV3** (JAX) — Minecraft (Diamond) and ProcGen CoinRun
- **LeWM** (JEPA-based world model) — Cube manipulation and PushT

The page (`index.html`) is a single static file — open it directly or serve it with any static
server (e.g. `python -m http.server`).

## Adding the epoch-comparison clips

Each task has placeholder slots for per-epoch clips. Drop a `.mp4` (or `.gif`) at the path printed
under each slot, then swap the placeholder `<div class="media-placeholder">…</div>` for a
`<video autoplay muted loop playsinline></video>` (or `<img>`) pointing at it:

```
static/videos/cube/      epoch0.mp4   epoch10.mp4  epoch20.mp4
static/videos/pusht/     epoch0.mp4   epoch200.mp4 epoch1000.mp4
static/videos/minecraft/ step02m.mp4  step1m.mp4   step23m.mp4
static/videos/coinrun/   early.mp4    mid.mp4      final.mp4
static/videos/teaser.mp4 (optional hero clip)
```

## TODO before publishing

- Fill in your name / affiliation / resume link in the hero (`<!-- TODO -->` markers in `index.html`).
- Point the "LeWM Code" GitHub button at the real repo URL.
- Drop in the epoch clips (see above).

## Template credit

Built on the [Nerfies](https://github.com/nerfies/nerfies.github.io) project page template,
licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
