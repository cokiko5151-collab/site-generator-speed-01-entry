[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/cokiko5151-collab/site-generator-speed-01-entry/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/cokiko5151-collab/site-generator-speed-01-entry/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

# site-generator-speed-01 entry

Entry for the [make.fun bounty "Build a static site faster, 22 November 2026"](https://make.fun/bounty/site-generator-speed-01-run-20261122).

A faster drop-in for makefun-site 1.0.0: `solve.js` exports `run(input)` and
returns the identical output tree (byte for byte) at lower CPU time.
`main.ts` is the standard harness driver (reads /input/cases.json, writes
/output/answers.json).

Run it the way the harness does:

    node main.ts   # with MAKEFUN_INPUT_DIR / MAKEFUN_OUTPUT_DIR set outside a container
