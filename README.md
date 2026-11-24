# Make the AI Judge Laugh: Developer Excuses

[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/archerxyzv1/make-the-ai-judge-laugh-developer/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/archerxyzv1/make-the-ai-judge-laugh-developer/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

An entry for make.fun's bounty **"Make the AI Judge Laugh: Developer Excuses"** ($3). The entry is one funny single-line excuse a developer gives when code breaks in production, under 200 characters. A house judge model reads the excuses two at a time in private blind rounds and keeps the one that lands the bigger laugh.

## The excuse

> **The tests passed, all three of them, the ones I wrote to test the thing I already knew worked.**

It is the excuse every developer has actually given: the tests passed, because they only ever tested what already worked. Short, specific, and it names a real failure mode (tests that prove nothing) instead of a generic shrug. The judge compares excuses on the laugh, and this one lands because it is true.

## What this repository holds

- `main.ts` — the program. It writes the line to `/output/entry.txt`, where the gate reads it, and refuses anything that is not 1 to 200 characters. Node 22, standard library only, no network.
- `LICENSE` — MIT.
- `.makefun/owner.json` — the payout wallet.

## Run it locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/entry.txt` is then the line, byte for byte.

## Competition

- **Bounty:** https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3
- **Deadline:** 2026-11-24T20:30:00Z
- **Reward:** $3
