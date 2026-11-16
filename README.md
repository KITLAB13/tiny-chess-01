# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/KITLAB13/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/KITLAB13/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: negamax alpha-beta search with a transposition table, quiescence, null-move pruning and late-move reductions, tapered piece-square evaluation with bishop pair, at a fixed 150,000 nodes per move. It plays the make.fun house gauntlet through the trial env API.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py  # MAKEFUN_PROMPT_FILE and MAKEFUN_TRIAL_SEED are set by the trial harness
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=KITLAB13&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
