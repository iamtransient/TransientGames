# Transient Mini Games

A collection of lightweight, single-file browser games built under the **Transient** brand — signature deep-space aesthetic with neon cyan/magenta accents, glassmorphism, and zero-dependency HTML.

No build step. No installs. Every game is one `.html` file you can open directly in a browser.

---

## 🎮 Games

| Game | File | Description |
|---|---|---|
| 🧩 Number Sliding Puzzle | [`slide-puzzle.html`](./slide-puzzle.html) | Classic 15-puzzle with 3×3/4×4/5×5 modes, smooth GPU-accelerated tile animations, move counter, timer, and saved best scores. |
| 🗼 Tower of Hanoi | [`tower-of-hanoi.html`](./tower-of-hanoi.html) | Move the stack between pegs in the fewest moves, with adjustable disk count and move validation. |
| ♟️ Chess | [`chess.html`](./chess.html) | Full two-player chess with legal move validation, check/checkmate detection, and captured-piece tracking. |
| ⭕ Tic Tac Toe | [`tic-tac-toe.html`](./tic-tac-toe.html) | Classic 3×3 grid with single-player (minimax AI) and two-player modes. |
| 🧱 Tetris | [`tetris.html`](./tetris.html) | 90s-style Tetris with SRS rotation, hold/ghost piece, 7-bag randomizer, and full mobile controls. |


## 🚀 Getting Started

Clone the repo and open any game directly in a browser — no dependencies, no build process.

```bash
git clone https://github.com/<your-username>/transient-mini-games.git
cd transient-mini-games
open slide-puzzle.html   # or just double-click the file
```

Or serve the folder locally to try everything at once:

```bash
npx serve .
```

## ✨ Design Language

- **Palette:** void-black backgrounds, neon cyan (`#00e5ff`) + magenta (`#ff2fa0`) accents, lime highlights
- **Typography:** Orbitron (display) + JetBrains Mono (UI/data)
- **Style:** glassmorphism panels, subtle glow/shadow effects, fully responsive
- **Format:** every game is a single self-contained `.html` file

## 📁 Repo Structure

```
transient-mini-games/
├── slide-puzzle.html
├── tower-of-hanoi.html
├── chess.html
├── tic-tac-toe.html
├── tetris.html
└── README.md
```

## 🛠️ Stack

Pure HTML/CSS/JavaScript — no frameworks, no build tools, no runtime dependencies (Google Fonts loaded via CDN for typography only).

## 🤝 Contributing

Issues and PRs are welcome — new games, bug fixes, or performance tweaks all fit the spirit of this repo. Please keep new additions to the single-file format and existing design language.

## 📄 License

MIT — see [LICENSE](./LICENSE) for details.
