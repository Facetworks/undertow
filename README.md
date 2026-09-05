# Undertow

**Stir the current.** A real-time GPU fluid simulation in your browser: drag to pour dye into a stable-fluids solver and watch it fold, split, and fade. WebGL2, no server, no dependencies, no build step.

**→ Live: https://undertow.signalizeai.org**

## What it is

A Jos Stam stable-fluids solver running entirely in fragment shaders. Velocity and dye live in floating-point textures; every frame advects the velocity field, solves pressure with 20 Jacobi iterations, subtracts the gradient, then advects the dye. From those passes, smoke-like currents appear that never repeat.

## Controls

- **Drag** — stir dye into the current; fast strokes pour more
- **Palette** — Lagoon / Ember / Bloom / Ghost dye sets
- **Pause**, **Reset**, and a live fps readout
- Leave it alone for a few seconds and it stirs itself

## Run locally

Open `public/index.html` in a browser, or serve the folder:

```bash
npx serve public
```

## License

MIT
