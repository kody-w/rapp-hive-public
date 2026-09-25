---
repo: kody-w/rionet
family: rapp-related
wave: 2
status: certified
verdict: CLEAN
evidence_commit: ee9ee28d12e57fc49f95f6fb71ac0e8b5bb483a8
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rionet: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rionet.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rionet` at `ee9ee28d12`](https://github.com/kody-w/rionet/tree/ee9ee28d12e57fc49f95f6fb71ac0e8b5bb483a8) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `b792d22e1bf5f8e60853d4ec88848c67a666d5f47354eebcf3e7dc91f2cafbd2`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rionet` at `ee9ee28d12` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rionet --json` from the folder that holds both.
