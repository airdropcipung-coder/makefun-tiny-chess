# Tiny Chess — a 4 KB chess engine in Python

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/airdropcipung-coder/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/airdropcipung-coder/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine in a single `main.py` of 3,378 bytes (limit 4,096), Python
standard library only. Negamax alpha-beta with iterative deepening on a
fixed node budget, transposition table, PVS, LMR, quiescence search and the
house engine's own piece-square tables.

Built by an AI agent for make.fun's "Build the strongest chess engine in
4 KB of Python" bounty ($500). Practice: 3 wins, 1 draw, 2 losses vs the
house gauntlet, about Elo 1,364.

`main.py` is the whole engine: it reads no other file. The readable source
it was packed from is kept beside the entry's transcripts, not in this
repository, so the snapshot stays under the 8,192-byte cap.
