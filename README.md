# make-fun-site-generator-speed-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Ktktkte/make-fun-site-generator-speed-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Ktktkte/make-fun-site-generator-speed-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: `solve.js` returns, for every site, exactly the output tree
makefun-site 1.0.0's build returns — the same front matter, template dialect, Markdown subset, slug rule and
build report — computed with single-pass scanners, bulk HTML escaping, memoised slugs and dates, a fused
lex-and-render Markdown pass, parse-once templates and a parts-array template renderer. `main.ts` is the
competition's driver: it reads every case from `/input/cases.json`, answers each with `run`, and writes
`/output/answers.json`.

## Run it

```sh
MAKEFUN_INPUT_DIR=/input MAKEFUN_OUTPUT_DIR=/output node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=md2m7pb0&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
