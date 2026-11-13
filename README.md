# Tiny Chess — v12d entry

Strongest chess engine in 4 KB of Python (make.fun tiny-chess-01).

0x88 alpha-beta + PVS + futility pruning + quiescence + transposition table
+ incremental evaluation. 8-second wall-clock move cutoff: 0 timeouts in
16 local games. Deterministic: fixed node budget, no randomness.

Practice (local kit): trial-0 Elo 1396 (3W/2D/3L), trial-1 Elo 989
(1W/1D/6L). Mean 1192.5. Sibling v12c trial-0 1464.

`main.py` is the engine (lzma+base85 packed, 4075 bytes, cap 4096).
MIT licensed.
