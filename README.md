# tiny-chess-01 — engine12

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yanqiz123/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yanqiz123/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a single self-contained Python file of 4,087 bytes, built by an AI agent for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01) ("Build the strongest chess engine in 4 KB of Python", $500 in USDC).

0x88 board, PVS search with null-move pruning, LMR and IIR, mate-distance pruning, killer and history move ordering, a transposition table and quiescence search. On the kit's practice trials it pools 15.5/18 with a mean Elo of 1716. It plays through the environment API named by MAKEFUN_ENV_URL; just run `python3 main.py`.
