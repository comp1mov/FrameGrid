# FrameGrid

**Browser-based tool for video frame extraction, grid visualization, and frame-by-frame drawing.**

FrameGrid samples any video into a grid of frames — turning the flow of time into a spatial layout where the structure of motion becomes visible at once. Draw animations directly on the grid, export contact sheets, or build storyboards for documentation and sharing. Everything runs locally in your browser.

→ **[Live version](https://comp1mov.github.io/FrameGrid)**
→ **[Tutorial](https://www.youtube.com/comp1mov)**
→ **[Support](https://buymeacoffee.com/comp1mov)**
→ **[Feedback](https://forms.gle/h8SZKABkCN17TdM26)**
→ **[grisha-tsvetkov.com](https://grisha-tsvetkov.com)**

---

## What it does

Video is an illusion of motion built from still images. FrameGrid inverts this: it takes your video back into individual frames and arranges them in a single spatial grid — where rhythm, repetition, and movement patterns become readable as structure.

- Sample any video into 1–1000 frames, distributed evenly or at custom intervals
- Arrange frames in a fully configurable grid (columns, aspect ratio, spacing, loop phases)
- Draw frame-by-frame animations with a **Template layer** that paints across all frames simultaneously
- Export as PNG contact sheet, MP4 animation, or PNG sequence with alpha drawings
- Works with image sequences — load 1 to 200 images, frames distributed evenly across the grid
- Install as a **PWA** on desktop or mobile — works fully offline

---

## Import formats

**Video:** MP4, MOV, WebM, AVI, MKV, OGV, M4V
> Playback depends on browser codec support. MP4 (H.264) has the widest compatibility.
> Recommended: Chrome 94+, Edge 94+, Safari 16.4+

**Images:** PNG, JPG, WEBP, GIF (up to 200 files at once)

---

## Export

| Format | Description |
|---|---|
| **JPEG 2K** | Contact sheet up to 2K resolution |
| **PNG Full** | Full original resolution contact sheet |
| **MP4 Grid** | Animated grid as H.264 video |
| **MP4 Single** | Single-frame playback as H.264 video |
| **PNG Sequence** | ZIP of individual frames with optional alpha drawings |

---

## Drawing system

- **Background** — draws on the whole grid as one canvas
- **Template** — floating window that stamps your drawing onto every frame simultaneously
- **Frame** — draws on individual frames separately

Tools: Round brush · Spray brush · Eraser
Controls: Size · Opacity · Edge Softness · Color picker · Recent colors · Auto video palette · Undo · Long Stroke

---

## Grid settings

- Frame count: fixed number, every N seconds, every N frames
- Start / End frame range
- Columns, cell size, spacing, auto-fit
- Canvas aspect ratio: Auto, 1:1, 16:9, 9:16, 4:3, 3:4
- Frame transform: scale, offset X/Y, crop aspect
- Loop phases
- Timecode overlay: index / seconds / frame — position, size, color, opacity

---

## Animation preview

- FPS: 1–60
- Direction: Forward, Backward, Ping-pong, Sync, Random
- Pattern: Sequential, Center-out, Snake, Vertical, Random
- Onion skin overlay

---

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Space` | Play / Stop |
| `M` | Toggle Menu |
| `D` | Draw Mode |
| `X` | Exit Draw Mode |
| `B / T / F` | Draw target: Background / Template / Frame |
| `E` | Eraser |
| `Z` / `Ctrl+Z` | Undo |
| `C` | Clear current target |
| `P` | Toggle Brush Palette |
| `L` | Long Stroke |
| `R` | Regenerate Grid |
| `[ ]` | Brush Size |
| `Shift + [ ]` | Edge Softness |
| `Ctrl + [ ]` | Brush Opacity |
| `+/-` | Step Frame |
| `Home / End` | Jump Start / End |
| `Esc` | Close / Stop |

---

## Installation

FrameGrid is a single HTML file — no build step, no dependencies, no install required.

**Option 1 — use online:**
Open the live version in Chrome, Edge, or Safari.

**Option 2 — run locally:**
Download `framegrid.html` and open it directly from your filesystem.

**Option 3 — install as PWA:**
Open in Chrome or Edge → browser menu → "Install App" / "Add to Home Screen".
Works fully offline after install. Compatible with desktop and mobile.

---

## Roadmap

**Current version** — free, browser-based, single HTML file, works offline and as PWA.

**Pro version (planned)** — standalone desktop app (Windows / macOS), single payment:
- Project files — save and load sessions
- Animation layers
- No resolution limits
- Extended export options

The browser version will always remain free.

---

## About

Made by [Grisha Tsvetkov](https://grisha-tsvetkov.com)
© 2026 · [grisha-tsvetkov.com](https://grisha-tsvetkov.com)
