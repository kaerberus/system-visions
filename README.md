# System Visions

An interactive Mondrian-style art toy. Three layered cartesian grids are drawn
into canvas textures, fanned through depth in 3D, and can be flattened,
exploded, reshuffled, or sent into *infinity mode* — where the pattern spreads
past the frame to the edges of the viewport.

## Run it

Open `system-visions.html` in a browser. There is no build step; three.js is
loaded from a CDN.

## Controls

- **Top / 3D view** — flatten the layers into a single composition, or fan them
  back out through depth.
- **Explode / collapse** — lay the three grids out side by side.
- **Shuffle** — regenerate every grid: its cuts, its fills, and which colour
  sits in which layer.
- **Infinity mode** — tile the pattern out to the viewport edges, lines first
  and then the cells. The title slides in on a black plate and its fill drains
  away to reveal a freshly randomized red / blue / yellow gradient drifting
  through the letters.

Drag to orbit, scroll to zoom. Both are disabled while infinity mode is on.

## License

MIT — see [LICENSE](LICENSE).
