---
repo: kody-w/rapp-twin
family: twins
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 588feadbf37b2efa76eca74a6bbdd9523bd711c9
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-twin: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-twin.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-twin` at `588feadbf3`](https://github.com/kody-w/rapp-twin/tree/588feadbf37b2efa76eca74a6bbdd9523bd711c9) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `8b7be731705e43b437c56e7af1f99e39488e0e40fdce3646be0ececd41bfddd7`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-twin` at `588feadbf3` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-twin --json` from the folder that holds both.
