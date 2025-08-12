# Vibe-coded Tetris — Almost oneshotting a browser puzzle game

<img width="836" height="810" alt="image" src="https://github.com/user-attachments/assets/1c2e8a34-874f-4223-a2a4-c757843944e6" />

**Version 1.0.6**

## Features
- Standard Tetris clone at it's core
- Ghost guide mode, which shows where your block is gonna land
- AI Assist mode, which places blocks for you. Aka the game plays itself..
- Konami code unleashes spectacular visual effects

## Why?
- To try out whether the (at the point of typing this) newly launched OpenAI's GPT-5 is as good in vibe-coding as they claim. And better than Claude's models..
- This was purely to showcase the capabilities of low-effort vibe-coding. It worked, rather well. Yet I don't even like the traditional Tetris as a pastime...

## How?
- I enabled GPT-5 mode in Microsoft 365 Copilot and prompted it to: "vibe-code me a tetris game using html and javascript. Give it a *insert company name here* twist, using the company's brand color and some easter egg in the source code and the gameplay from the website *companywebsite.com*"
- Well, it took 2 more prompts to get everything running without errors and 4 more prompts to add few visual and functional features.
- That's it! Try it yourself with the free ChatGPT UI and reimagine your favorite low-effort game with ease!
 
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
