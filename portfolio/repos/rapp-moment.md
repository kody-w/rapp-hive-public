---
repo: kody-w/rapp-moment
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 229db186c505d2f2a693fac41cbbe84cadf7a07c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-moment: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-moment.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-moment` at `229db186c5`](https://github.com/kody-w/rapp-moment/tree/229db186c505d2f2a693fac41cbbe84cadf7a07c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `8ac59f80e42d00e2e84991b9eb95a17465442e614266f89f0eb135d9932fee62`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-moment` at `229db186c5` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-moment --json` from the folder that holds both.
