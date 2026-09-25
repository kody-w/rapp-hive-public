---
repo: kody-w/rapp-map
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 81dd6f05ab0969d11253f3fe7f4834288824d17e
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 54
header: missing
---

# rapp-map: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-map.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/rapp-map` at `81dd6f05ab`](https://github.com/kody-w/rapp-map/tree/81dd6f05ab0969d11253f3fe7f4834288824d17e) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s), 26 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `c37cc9c787beea0c40fc8065b10b80eafa3b55e295cc43a4e9f44f3579f3f8b0`.
- "experimental" mentions: 54 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `spine/vertebrae/estate-2026-07-25.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rapp-map` at `81dd6f05ab` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-map --json` from the folder that holds both.
