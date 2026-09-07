# Neon Dodge

A fast-paced, cyberpunk-styled arcade survival game built with vanilla JavaScript and the HTML5 Canvas API — no frameworks, no dependencies, no build step.

**[Play it live →](#)** *(update this link once deployed)*

![difficulty](https://img.shields.io/badge/difficulty-easy%20%7C%20normal%20%7C%20hard-29f0ff)
![tech](https://img.shields.io/badge/built%20with-JS%20%2B%20Canvas-8b5cf6)

## About

Steer a glowing orb through a storm of drifting geometric obstacles. The longer you survive, the faster and denser the field gets. Cutting it close — grazing an obstacle without hitting it — builds your combo multiplier and ramps your score. One real hit ends the run.

## Features

- **Mouse / touch / keyboard controls** — move naturally with your cursor, or use WASD / arrow keys
- **Combo scoring system** — near-misses build a multiplier that boosts your score rate
- **Three difficulty modes** — Easy, Normal, and Hard, each tuning obstacle speed, spawn rate, and score multiplier
- **Procedural sound design** — every sound effect (graze blips, combo fanfare, crash noise) is synthesized in real time with the Web Audio API — zero audio files, zero load time
- **Pause / resume** — pause button, `Esc` key, and auto-pause when the tab loses focus
- **Persistent high score** — saved locally via `localStorage`
- **Particle effects & screen shake** — glowing trails, graze bursts, and impact feedback for game-feel polish
- **Fully responsive** — canvas resizes to fill any viewport

## Tech Stack

- Vanilla JavaScript (no frameworks)
- HTML5 Canvas for rendering
- Web Audio API for procedural sound effects
- `localStorage` for high score persistence

## Running locally

This is a single self-contained HTML file — no build step, no dependencies.

```bash
git clone https://github.com/kelechicodes-dev/neon-dodge.git
cd neon-dodge
open index.html
```

Or just double-click `index.html` in any modern browser.

## Controls

| Input | Action |
|---|---|
| Mouse / touch | Steer the orb |
| `W A S D` / Arrow keys | Steer the orb |
| `Esc` | Pause / resume |
| Space | Start / retry from menu |

---

Built by [Kellz](https://kelechicodes-dev.github.io/kelechi-portfolio/)
