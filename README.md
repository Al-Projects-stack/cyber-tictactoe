# ⚡ Cyber Tic-Tac-Toe

A dark cyberpunk-themed 3D Tic-Tac-Toe game built with Flask and vanilla JavaScript.

## Features

- **3D board** — 3 layers of 3×3 grids played simultaneously across all 5 rounds
- **Best-of-5 match** — first player to win 3 rounds takes the match
- **3 round themes** — Pink/Blue (round 1) → Orange/Purple (round 2) → Red/White (rounds 3–5)
- **vs AI mode** — Easy (random) or Hard (win/block heuristic)
- **Warp animation** — portal effect on game start
- **Floating pieces** — CSS 3D depth effects with neon glow on placed pieces
- **Winner overlay** — scan-line animation on match end

## Setup

```bash
pip install -r requirements.txt
python app.py
```

Then open `http://localhost:5550` in your browser.

## How to Play

1. Enter player names and choose **2 Players** or **vs AI**
2. Click **Initialize** to warp into the arena
3. Click any cell across the 3 layers to place your piece
4. Win 3 in a row — horizontally, vertically, diagonally, across layers, or through space diagonals
5. First to win 3 rounds wins the match

## Stack

- **Backend:** Python / Flask
- **Frontend:** Vanilla JS, CSS (Orbitron font, CSS animations)
- **No database** — all game state is client-side
