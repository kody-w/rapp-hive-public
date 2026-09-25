---
repo: kody-w/rio
family: rapp-related
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 1062e28e3592d272fad5dae2b0b2c17511ce25ef
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rio: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rio.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/rio` at `1062e28e35`](https://github.com/kody-w/rio/tree/1062e28e3592d272fad5dae2b0b2c17511ce25ef) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `2ab5d7f4a46f2c1962791d22947d4d9b930b20c8292df0514edcec31659dc074`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `rio.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rio` at `1062e28e35` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rio --json` from the folder that holds both.
