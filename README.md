# NEON CLASH 1V1 — Web Build v2

Playable browser fighting game prototype using HTML/CSS/JavaScript and Canvas 2D. No build step or server required.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. For the most reliable behavior, host the folder using GitHub Pages, Netlify, or another static host.
3. On a phone, rotate to landscape.
4. Select **MASUK ARENA**. Tap the mode card to switch between **VERSUS AI** and **TRAINING**.

## Controls
- Move: A/D or arrow keys, or touch joystick
- Punch: J / FIST; Kick: K / KICK; Skill: L / SKILL (requires 35 energy)
- Jump: I / JUMP; Block: hold O / BLOCK button; Dodge: U / DODGE
- Pause: Esc / pause icon

## Included
- Cinematic-style boot screen with initialization progress and skip button
- Animated Canvas lobby fighter, neon arena, responsive layout and portrait rotation prompt
- Versus AI and training mode, punch, kick, skill, jump, block, dodge, health/energy HUD, timer, hit particles, rewards, pause and rematch
- Fighter/skin/event/settings pages, tutorial, synthesized sound effects via Web Audio
- Local coin/win/match persistence via `localStorage`

## Publication status — read before release
This is a **playable web prototype/foundation**, not a verified commercial release. Characters and arena are procedural Canvas artwork rather than production sprite sheets or 3D models. The boot percentage represents app initialization checkpoints, not download progress for external art/audio. Profile, coins and stats are local to one browser and are not secure online accounts. Online multiplayer, server-authoritative ranked mode, cloud save, real payments, licensed music and an Android package are not included.

Before publishing: test on target phones/browsers, fix any issues found, add original/licensed art and audio, implement backend/security features if required, create a privacy policy and store disclosures, package the web game in an Android wrapper such as Capacitor, and complete Play Console testing/review. Do not advertise online features that are not implemented.
