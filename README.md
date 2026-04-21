# GRAINHAUS
A personal vintage film camera — built as a PWA (Progressive Web App). No app store. No installs. Just open the link in your browser and shoot.

---

## What it is
Grainhaus is a browser-based camera app that applies real film emulation on top of your phone's camera. Every shot gets grain burned in, a date stamp like old cameras, and the color grade of whatever film preset you're shooting on. Photos save to your camera roll at full resolution.
Built for personal use. Not on any app store.

---

## Film Presets

| Preset | Vibe |
|---|---|
| **Kodak 400** | Warm tones, classic grain, golden shadows |
| **Fuji 400H** | Cool greens, soft contrast, clean highlights |
| **Portra 800** | Rich skin tones, heavy grain, pushed look |
| **HP5 B&W** | High contrast black & white, punchy grain |
| **Velvia 50** | Saturated, vivid colors, sharp and clean |
| **Lomo LC-A** | Crushed blacks, heavy vignette, lo-fi chaos |

---

## Features

- Live animated film grain on the viewfinder
- 6 film presets with real color grading
- Grain and vignette baked into every saved photo
- Amber date stamp burned into the image
- Full-resolution capture (shoots at your phone's native camera resolution)
- Shot roll gallery with one-tap download
- Flip between front and rear camera
- Installs on your home screen like a real app (PWA)

---

## How to use it on your phone

> You need to open it via `https://` — not from a local file. Camera permissions don't work on `file://` paths in Chrome.

### Option 1 — GitHub Pages (recommended)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your app will be live at `https://yourusername.github.io/grainhaus/`
5. Open that URL in **Chrome (Android)** or **Safari (iPhone)**
6. Allow camera when prompted

### Option 2 — Netlify Drop (fastest, no account needed)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `grainhaus.html` onto the page
3. Get your live URL instantly
4. Open on phone, allow camera, shoot

---

## Install as an app (Add to Home Screen)

**Android (Chrome):**
Tap the 3-dot menu → *Add to Home Screen*

**iPhone (Safari):**
Tap the Share button → *Add to Home Screen*

Once installed it opens full screen with no browser bar — feels like a real camera app.

---

## Files

```
grainhaus.html   — the entire app
manifest.json    — PWA manifest (enables home screen install)
README.md        — this file
```

---

## Tech

Pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build step. Everything is in one file. Works offline after first load.

---

*Made for personal use. Shoot on film.*
