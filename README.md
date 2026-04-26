# LEGO Color-by-Number Pipeline

Upload an image, crop it square, pick a palette (LEGO 20 included), and get a
gridded color-by-number plus solution view that you can build with LEGO bricks.

All image processing runs client-side in the browser — no server, no uploads.

## Deploying on Render

This repo is configured as a Render **Static Site** via `render.yaml`.
On Render, click **New → Static Site**, connect this repo, accept the defaults,
and it'll publish `index.html` at the root.
