# Tiny Chess — round-3 entry (v7)

Strongest chess engine in 4 KB of Python (make.fun tiny-chess-01).

0x88 alpha-beta + quiescence + transposition table + null-move pruning +
late-move reductions + aspiration windows + killer moves + history
heuristic. No king pawn-shield (removed in v7). Deterministic: fixed node
budget, no clock, no randomness.

Practice trial-0 (local kit level 6): Elo 1253 (3W/5L). Trial-1: Elo 1087
(2W/6L). Mean 1170 — below v4g mean 1221. No prize as-is.

`main.py` is the engine (lzma+base85 packed, 3925 bytes, cap 4096).
MIT licensed.
