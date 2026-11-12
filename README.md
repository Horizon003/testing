# Bao Panda Playground

A static web playground for the Bao Masko animation canvas.

## Run
Open with a local static server (e.g. `python -m http.server 8000`) or deploy to Vercel as an Other/static project.

The site plays the public WebM videos referenced by `bao-canvas.json`, with buttons for all supplied transitions and states. This is not the official Masko player SDK. The canvas JSON is a browser-compatible reconstruction of the provided delivery file with the same state/action IDs and public WebM references; it omits original thumbnails, HEVC alternatives, and some metadata. For the exact original delivery JSON, use the original attachment from Masko.
