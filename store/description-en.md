# Num Fusion — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Slide the board, fuse equal numbers and chase 2048. Classic merge puzzle with
smooth animations, undo moves and a glowing neon board. How far can you fuse?

(196 characters — fits the ≤200 limit)

## Details

- Genre: Puzzle / Casual / Numbers / Merge
- Controls: Arrow keys or WASD on desktop; 4-direction swipe on touch screens
  (30px threshold); mouse drag works too. Z or the Undo button reverts the
  last move (3 undos per game).
- Features: classic 2048 rules (tiles merge at most once per move, new tiles
  spawn 90% as 2 / 10% as 4), 150ms slide & merge tween animations, merge
  pulse, particles, float scores, win at 2048 with "Keep Playing" to chase
  4096 / 8192 and beyond, undo ×3 per game, best score saving, mute toggle,
  color ladder from cold blue to gold with auto-shrinking numerals.
- Tech: Vanilla JavaScript, Canvas, WebAudio (all sounds synthesized at
  runtime). Single-file HTML5, no external assets, works offline once
  loaded. No frameworks, no tracking.

## Tags
2048, merge, numbers, puzzle, casual, swipe, brain, logic, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload num-fusion-gd.zip (index.html only, 30.1KB)

## itch.io
- Upload num-fusion-itch.zip (rename to num-fusion.zip if preferred), mark
  "This file is playable in browser", entry file: index.html, viewport
  480×560, kind: html
- Pricing: $0 (donations optional)
