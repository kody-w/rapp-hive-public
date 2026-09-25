---
repo: kody-w/rapp-virtual-as400
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 2b510ed0b97d24f9423be2a0a7eb7d2e54d52887
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-virtual-as400: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-virtual-as400.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-virtual-as400` at `2b510ed0b9`](https://github.com/kody-w/rapp-virtual-as400/tree/2b510ed0b97d24f9423be2a0a7eb7d2e54d52887) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ec20687630ab13fe63d24f1c8257d7be88cd1c1f90c29944475bc714a82ede65`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-virtual-as400` at `2b510ed0b9` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-virtual-as400 --json` from the folder that holds both.
