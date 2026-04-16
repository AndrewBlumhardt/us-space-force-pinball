# 🚀 US Space Force Pinball

A browser-based neon pinball game inspired by US Space Force visuals and mission themes.

Launch your rocket, chain combo multipliers, dodge drifting asteroids, and earn resupply drops to keep the mission alive. Six flippers, dynamic space events, and a mission-control banter system keep each run fresh.

## ▶️ Play Live

<a href="https://www.techchat.blog/wp-content/uploads/2026/04/orbital-guardian.html" target="_blank">
  <img src="https://img.shields.io/badge/▶%20Play%20Orbital%20Guardian-Live%20Demo-70ddff?style=for-the-badge&labelColor=08112d" alt="Play Orbital Guardian">
</a>

Also hosted at: [andrewblumhardt.github.io/us-space-force-pinball](https://andrewblumhardt.github.io/us-space-force-pinball/)

## How to Play

Open `orbital-guardian.html` in any modern browser - or [play the live version](https://www.techchat.blog/wp-content/uploads/2026/04/orbital-guardian.html).

| Control | Action |
|---------|--------|
| `Space` (hold/release) | Charge and launch |
| `Left Arrow` | Left flippers |
| `Right Arrow` | Right flippers |
| `Enter` | Restart after game over |
| Pointer / Tap | Mobile-friendly launch and flipper input |

## Gameplay Features

| Feature | Description |
|---------|-------------|
| Multi-flipper layout | 3 flippers per side for more combo control |
| Shooter lane launch FX | Shuttle-style plume and launch glow |
| Space-themed targets | NOVA, DELTA, ORBIT, SAT, COM bumpers |
| Dynamic hazards | Asteroids and moving event effects |
| Scoring system | Combo timer with up to x5 multiplier |
| Sound controls | In-game volume slider and mute toggle |

## Scoring

| Event | Points |
|-------|--------|
| Standard target hit | 100 |
| Combo multiplier (up to x5) | 2x - 5x base |
| Rocket launch bonus | 500 |
| Resupply earned | 12,000 base, +6,000 each time |

Keep the combo timer alive to stack multipliers. Resupply thresholds increase each time, so push for high scores early.

## Theme and Visuals

- Delta-globe-orbit inspired neon color palette
- Astronaut mission-control avatar with live banter
- USSF-flavored status commentary with classic space movie quotes mixed in
- Space Force bumpers: NOVA, DELTA, ORBIT, SAT, COM

## About

Built as an AI-assisted coding demo and iterative design project.

The game is intentionally single-file and browser-native - no build toolchain, no dependencies, nothing to install. Open the file, play the game.

## Stack

- Vanilla HTML5 Canvas + JavaScript
- Single self-contained file (`orbital-guardian.html`)
- No dependencies, no framework, no build toolchain

## Local Run

1. Clone this repository.
2. Open `orbital-guardian.html` in your browser.

Optional local server:

```powershell
cd us-space-force-pinball
python -m http.server 8080
```

Then browse to `http://localhost:8080`.

## License

[MIT](LICENSE)
