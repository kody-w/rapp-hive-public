---
repo: kody-w/rapp-hatchery
family: grail
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 9af32d050773ea696d9e611183526b9ebb336956
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 4
header: missing
---

# rapp-hatchery: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-hatchery.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-hatchery` at `9af32d0507`](https://github.com/kody-w/rapp-hatchery/tree/9af32d050773ea696d9e611183526b9ebb336956) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f4d41c5b71be473ec729ef0e00299fcee514fd3f4895d4c9e5e5fd104339317f`.
- "experimental" mentions: 4 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-hatchery` at `9af32d0507` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-hatchery --json` from the folder that holds both.
