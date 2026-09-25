---
repo: kody-w/RAPPcards
family: binders-cards
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 5bfcea8d6aaa78e988827783b44e0d384ed3c14a
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# RAPPcards: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPPcards.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/RAPPcards` at `5bfcea8d6a`](https://github.com/kody-w/RAPPcards/tree/5bfcea8d6aaa78e988827783b44e0d384ed3c14a) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `968e50bac9d1d60e98fc1be165180d4a88085f5af3344d91adca3a662684ae23`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/RAPPcards` at `5bfcea8d6a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPPcards --json` from the folder that holds both.
