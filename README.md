# 🚀 SHUTTLE: VOID RUNNER

A single-file, neon synthwave arcade shooter built with Three.js and the Web Audio API — no build step, no dependencies, no server needed.

**Play:** open `index.html` in any modern browser.

## Gameplay

Pilot your interceptor through an endless neon canyon at ever-increasing speed.

- **Dodge** asteroids and hunter drones — collisions cost hull; lose all hull and you burn a life (3 lives per run).
- **Auto-cannons** — hold to fire, shred rocks and drones for combo-multiplied score.
- **Barrel roll** — invincible dodge move with its own cooldown; phase straight through obstacles.
- **Overdrive** — hold boost to accelerate, widen your view, and regenerate the boost meter when idle.
- **Energy orbs** restore hull and stack your combo.
- Difficulty (spawn rate + world speed) ramps continuously with distance.

## Controls

| Input | Action |
|---|---|
| Mouse / Touch | Steer |
| Hold Left Click / Space | Fire (auto-cannons) |
| Shift / W | Overdrive boost |
| A / D | Barrel roll dodge |
| P / Esc | Pause |

## Features

- 100% client-side, single `index.html` — GitHub Pages ready
- Procedural Web Audio soundtrack + SFX (zero audio files)
- Screen shake, damage flash, particle explosions, shield-ring FX
- Combo multiplier, lives, invulnerability window, persistent high score (localStorage)
- Mobile touch support and responsive HUD

## Tech

- [Three.js r128](https://threejs.org/) via CDN — the only external dependency
- Vanilla JavaScript, no build tools

## Deploy (GitHub Pages)

1. Push `index.html` to the `main` branch root.
2. Repo **Settings → Pages → Source**: deploy from `main` / `/(root)`.
3. Site appears at `https://aasoftir.github.io/shuttle-game/`.
