# iPhone 17 Wallpaper Resizer

A minimal, zero-dependency browser tool that resizes any photo to the exact pixel dimensions of iPhone 17 series screens — ready to set as a wallpaper with no cropping or black bars.

## Live Demo

Open `index.html` directly in any browser. No server, no install.

## Features

- **Drag & drop** any photo (PNG, JPG, WEBP, HEIC)
- **All iPhone 17 models** supported
- **Exact pixel output** — full-resolution PNG download
- **Live preview** inside a phone frame so you see exactly what it'll look like
- **Zero dependencies** — single HTML file, works offline

## Supported Models

| Model | Resolution |
|---|---|
| iPhone 17 | 1206 × 2622 px |
| iPhone 17 Air | 1260 × 2736 px |
| iPhone 17 Pro | 1206 × 2622 px |
| iPhone 17 Pro Max | 1320 × 2868 px |

## How to Use

1. Open `index.html` in your browser
2. Drop your photo onto the page (or click **Browse files**)
3. Select your iPhone 17 model from the dropdown
4. Click **Download PNG**
5. Set the downloaded file as your iPhone wallpaper

## How It Works

Uses the browser's Canvas API to draw the image scaled to the exact target dimensions. No upload, no server — everything runs locally in your browser.

## Tech

- HTML / CSS / JavaScript — single file, ~390 lines
- Canvas API for image scaling
- FileReader API for local file loading
- No frameworks, no build tools

## License

MIT
