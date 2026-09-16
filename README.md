# Opening Trainer v3

Mobile-first chess opening trainer for GitHub Pages.

- Correct 8×8 mobile board.
- Stockfish 18 lite single-threaded browser engine.
- Player move compared with the engine recommendation.
- Simple result: excellent / inaccuracy.
- PWA icons and cache included.

Stockfish is loaded from a fixed UNPKG package URL; internet is required for the engine. The lite single-threaded build is intended for browser use and avoids the cross-origin isolation requirements of multi-threaded builds.
