---
repo: kody-w/rapp-shot
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: e99ca10658e6b8e0578051473d65faf3dbdc3e5f
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-shot: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-shot.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/rapp-shot` at `e99ca10658`](https://github.com/kody-w/rapp-shot/tree/e99ca10658e6b8e0578051473d65faf3dbdc3e5f) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `2288be7290234de5c140b9c21d3993207304485b18aa1d8c458fb002c576f110`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `rapp_shot/eggs/rapp_shot.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rapp-shot` at `e99ca10658` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-shot --json` from the folder that holds both.
