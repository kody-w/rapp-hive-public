---
repo: kody-w/rapp-kite
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: f3e7e2d04c30772d1abc0476da945a860fe226ab
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-kite: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-kite.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-kite` at `f3e7e2d04c`](https://github.com/kody-w/rapp-kite/tree/f3e7e2d04c30772d1abc0476da945a860fe226ab) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `9d0618f7bcf5c8f1567172cd821d3d1e2163d2a87025b02e44ff2d0b03da2af5`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-kite` at `f3e7e2d04c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-kite --json` from the folder that holds both.
