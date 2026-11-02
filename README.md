# Num Fusion · 2048 Merge

Free single-file HTML5 sliding number merge game. Classic 2048 gameplay on a
neon 4×4 board: swipe to slide, equal numbers fuse and double, reach 2048 to
win and keep chasing 4096 and beyond. One HTML file, zero assets.

**Play:** https://shuangyueliao.github.io/num-fusion/

- Arrow keys / WASD on desktop, 4-direction touch swipe on mobile (30px
  threshold), mouse drag also supported
- Classic 2048 merge rules (each tile merges at most once per move, 90/10
  spawn of 2s and 4s), smooth 150ms slide/merge tweens, merge pulse, particle
  bursts and float scores
- Undo (3 per game, restores the exact previous board and score), best score
  saved locally, mute toggle persisted
- Win screen at 2048 with "Keep Playing" to chase 4096, 8192 and beyond
- WebAudio synthesized sounds (slide / merge / win / lose), procedural canvas
  visuals, no dependencies, no tracking
