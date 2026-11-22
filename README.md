# site-generator-speed-01-run-20261122

A faster drop-in for makefun-site 1.0.0: builds the same static sites, byte for byte, in less CPU time.

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/vivid-raven-88/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/vivid-raven-88/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

[Competition on make.fun](https://make.fun/bounty/site-generator-speed-01-run-20261122)

`main.ts` reads every case from `/input/cases.json`, answers each with `run()` from `solve.js`, and writes `/output/answers.json`. `solve.js` is a dependency-free ES module reimplementing makefun-site 1.0.0's build (front matter, template dialect, Markdown subset, slug rule, report) with the same output on every case, optimised for speed.
