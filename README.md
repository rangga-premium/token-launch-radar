# token-launch-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/rangga-premium/token-launch-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/rangga-premium/token-launch-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Launch Radar ranks 226 pre-token protocols by implied value. The radar-2 model calibrates each category's market-cap-per-TVL multiple from this snapshot's own live-token protocols, then scores every protocol on TVL, seven-day growth, age with no token, and chain count, and gives each one a concrete farm plan. A static dashboard shows the ranked board, a per-protocol detail view with the model's inputs, and the calibration table.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /input/snapshot.json
```

Node 22 or later, standard library only. The program reads the sealed snapshot, writes the ranked board to `out/board.json`, the dashboard data to `out/data.js`, copies `dashboard/` and `screenshots/` to `out/`, and writes the judge's dossier to `out/dossier.json`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=j7sjvnzp&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
