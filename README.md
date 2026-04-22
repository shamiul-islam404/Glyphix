# Glyphix

> A lightweight, zero-dependency text analysis tool with a WebGL line-wave background.

**Glyphix** gives you two focused utilities in a single static page — a character density counter and a text slicer — wrapped in a dark glass UI with an animated WebGL background.

---

## Features

### 01 · Counter
- Live character count as you type
- Breakdown by **letters**, **digits**, **spaces**, and **unique** characters
- **Density Leaderboard** — every character ranked by frequency with a percentage and visual bar
- Filter the leaderboard by All / Letters / Digits / Other

### 02 · Slicer
- Paste any text and divide it into equal chunks by a chosen character count
- Shows total characters, number of parts, and the length of the last (remainder) part
- One-click **Copy** button on each slice

### Background
- Procedural **LineWaves** rendered in raw WebGL (no libraries)
- Reacts to mouse position with a smooth lerp
- Warm amber / apricot palette that complements the dark glass UI

---

## Tech Stack

| Layer | Details |
|---|---|
| HTML / CSS / JS | Vanilla — zero npm, zero build step |
| WebGL | Raw `WebGLRenderingContext` with custom GLSL shaders |
| Fonts | [Instrument Serif + Instrument Sans](https://fonts.google.com/) via Google Fonts |
| Hosting | [Vercel](https://vercel.com/) (static) |

---

## Getting Started

### Run locally

Just open [Glyphix](https://glyphix-main.vercel.app/) in any modern browser — no server or build step needed.

---

## Browser Support

Works in all modern browsers that support WebGL 1.0 (Chrome, Firefox, Safari, Edge). Falls back gracefully if WebGL is unavailable — the UI remains fully functional, just without the animated background.

---
