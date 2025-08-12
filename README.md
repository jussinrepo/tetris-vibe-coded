# Advania Tetris — People at Heart

Version 1.0.6

## What’s new
- **Ghost Guide toggle**: press **G** or click the **Ghost Guide** pill to show/hide the grey landing preview.

## Run
- Open `index.html` in any modern browser.

## Controls
- Left/Right: Move
- Up or X: Rotate clockwise; Z: Rotate counter‑clockwise
- Down: Soft drop (+1/row); Space: Hard drop (+2/row)
- **P**: Pause/Resume; **R**: Restart
- **G**: Toggle Ghost Guide (landing preview)
- Hidden: A then I → AI Assist (press H to auto‑place)
- Hidden: Konami code → Spiral of Success confetti

## Changelog
- 1.0: Initial version. Didn't render.
- 1.0.1: Fixed optional chaining assignment bug in `simulateDrop`, added spawn edge clamping and wall nudge for wide pieces, tightened hard/soft drop scoring updates.
- 1.0.2: Fixed black screen by scoping the canvas background to #board (fx overlay is transparent). Also includes prior bugfixes and spawn clamping.
- 1.0.3: Fixed rotation bug by switching to non-square-safe rotation (CW/CCW) and keeping wall-kick fallback; retains earlier bugfixes and canvas overlay transparency.
- 1.0.4: Brand color palette for blocks, plus previous rotation/overlay fixes.
- 1.0.5: Pause/resume fix, Visual polish
- 1.0.6: Ghost mode toggle

## Github
- https://github.com/jussinrepo/tetris-vibe-coded

## Credits
- Jussi Sivonen & OpenAI GPT-5 (dated 8.8.2025 aka launch day of the model)