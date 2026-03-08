# Screenshot Rescaler

A simple web tool that rescales screenshots from one resolution to another. Useful when moving images between different monitor resolutions (e.g. 1080p to 2K/4K). The rescaled image keeps the same aspect ratio but has pixel dimensions that match the target resolution.

## How to run

Open `index.html` in a modern web browser. No server or build step required — it’s a single self-contained HTML file.

You can:
- Double-click `index.html`, or
- Use **File → Open** in your browser and select `index.html`, or
- From a terminal: `start index.html` (Windows), `open index.html` (macOS), or `xdg-open index.html` (Linux)

## How to use

1. **Source resolution** — Choose (or enter) the resolution where the screenshot was taken (e.g. 1080p, 1440p, 4K, or custom).
2. **Target resolution** — Choose the resolution you want the image scaled to (e.g. your 2K/4K display).
3. **Drop or select an image** — Use the drop zone or click to pick a screenshot.
4. **Download** — Click “Download rescaled image” to save the scaled version as `rescaled.png`.

The page shows side-by-side previews of the original and rescaled image with dimensions and scale factor.

## Project structure

```
screenshot rescaler/
├── index.html   # Single-file app (HTML, CSS, JS)
└── README.md    # This file
```

No dependencies. Works offline.
