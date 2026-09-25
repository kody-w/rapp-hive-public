---
repo: kody-w/cowork-cookbook-rapp
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 2e2a3929c699cb6552ea8213c7a44f5a83acd389
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# cowork-cookbook-rapp: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/cowork-cookbook-rapp.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/cowork-cookbook-rapp` at `2e2a3929c6`](https://github.com/kody-w/cowork-cookbook-rapp/tree/2e2a3929c699cb6552ea8213c7a44f5a83acd389) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `257db8edaa3d37ee7b713f789195858216c2d7801b06d37ebcde749a306bfa24`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `cowork_cookbook.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/cowork-cookbook-rapp` at `2e2a3929c6` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py cowork-cookbook-rapp --json` from the folder that holds both.
