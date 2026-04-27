# LEGO Color-by-Number Pipeline

Upload an image (PNG, JPG, HEIC from iPhone, WEBP), crop it square, pick a
palette (LEGO Pick-A-Brick 64 by default), and get a gridded color-by-number
plus solution view, 3D stud preview, and a row-by-row printable build manual.

All image processing runs client-side in the browser — no server, no uploads.

## Deploying on Render

This repo is configured as a Render **Static Site** via `render.yaml`.
On Render, click **New → Static Site**, connect this repo, accept the defaults,
and it'll publish `index.html` at the root.
