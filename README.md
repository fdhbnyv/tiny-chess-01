# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/fdhbnyv/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/fdhbnyv/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny chess engine in under 4 KB of Python for the make.fun [tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).

## Features
- Alpha-Beta search with Negamax and Quiescence extension
- Piece-Square Table (PST) positional evaluation
- Move ordering: Transposition Table, MVV-LVA captures, killer moves
- Repetition avoidance / contempt score
- Strict <= 4096 bytes compressed size, Python 3.13 standard library only
