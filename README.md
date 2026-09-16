# Opening Trainer v5

Mobile-first chess opening trainer.

## Engine
Stockfish 18 Lite Single is started in a Web Worker using a Blob Worker URL. The
worker URL explicitly carries the remote WASM location, avoiding the common
failure where the engine looks for `stockfish-worker.wasm` instead of
`stockfish-18-lite-single.wasm`.

The engine and WASM are loaded from UNPKG, so internet access is required.

## Features
- Correct 8x8 mobile board
- Legal moves
- Stockfish recommendation
- Player move comparison
- Why? explanation
- PWA icons
