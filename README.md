# ECHO

A free, offline, single-file browser game — race against a recorded ghost of your own last attempt.

Cross dust, gravity, and the stars across 5 levels: **Dustbowl → Liftoff → Wormhole → Event Horizon → Singularity**.

## Play

Open `index.html` in any browser. No build step, no dependencies, no server required.

- **Up Arrow / Space** — jump (hold for a higher jump)
- **Down Arrow** — duck
- **Esc** — pause
- On touch devices, on-screen Jump/Duck buttons appear automatically

## How it works

Every run is recorded. Die or finish a level, and your next attempt plays out alongside a translucent ghost of your previous run. Land in sync with your ghost mid-air to build a score multiplier (up to ×5). Collect coins, shield power-ups (absorb one hit), and double-jump power-ups along the way.

Everything — music, sound effects, art, physics — is generated live in the browser:

- **Graphics**: HTML5 Canvas, procedurally drawn, device-pixel-ratio aware for sharp rendering on any screen
- **Audio**: synthesized with the Web Audio API (no audio files) — an original ambient score plus a ticking-clock tension motif
- **Persistence**: your best score is saved locally via `localStorage` (safe fallback if unavailable)

No external assets, no accounts, no tracking, no backend.

## Credits

A game by **SYP**.

## License

Free to play and share.
