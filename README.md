# token-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/error0702/token-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/error0702/token-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar ranks pre-token protocols by implied value — what a token would be worth if the protocol's record stayed as it is — and gives every protocol a concrete farm plan. The model (radar-2) scores TVL, seven-day growth, age with no token, category and chain breadth, and leaves wrapped, staked and bridged products out entirely.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input ./input/snapshot.json
```

Node 22.18 or later, standard library only. `main.ts` reads the sealed snapshot, writes the ranked board to `out/board.json`, the dashboard data to `out/data.js`, and copies `dashboard/` and `screenshots/` to `out/`, with `out/dossier.json` for the judge. Open `out/dashboard/index.html` in a browser to use the radar: search, filter by category, chain and TVL, sort, and open any row for its model breakdown and farm plan.

---

<sub>Entered on [make.fun](https://make.fun/?ref=z2ttv7s5&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
