# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/robbyensoe/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/robbyensoe/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, built for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01): negamax alpha-beta with PVS, null-move pruning, LMR, a transposition table, quiescence over captures and check evasions, and a tapered piece-square evaluation with a bishop-pair bonus. It searches to a fixed node budget (60,000 nodes per move), never a clock, so every trial replays move for move.

`main.py` is the whole engine, packed with `makefun compress` from a readable source. Python 3.13, standard library only. It plays through the env at `MAKEFUN_ENV_URL`.
