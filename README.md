# tiny-chess-01 entry

A chess engine in 4 KB of Python: negamax alpha-beta with PVS, null-move
pruning, LMR, a transposition table, quiescence over captures and check
evasions, and a tapered piece-square evaluation. It searches to a fixed
node budget (40,000 nodes per move), never a clock, so every trial replays
move for move.

`main.py` is the whole engine, packed with `makefun compress` from a
readable source. Python 3.13, standard library only.
