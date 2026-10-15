# Quad Fill Bench

A simple browser GPU benchmark built with WebGL2. It draws thousands of blended squares using instanced rendering and measures how well your GPU keeps up.

## How it works

- Four stages of 5 seconds each: 2,000, 10,000, 40,000 and 100,000 squares
- Live status, stage, FPS and frame time while it runs
- Per-stage average FPS and worst frame time
- Final score: average FPS per stage weighted by square count (higher is better)

## Run it

Open `index.html` in any modern browser, or enable GitHub Pages on this repo and visit the published URL.

Note: on a 60 Hz screen FPS is capped at 60, so the later stages are where devices separate.
