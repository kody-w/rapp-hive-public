---
repo: kody-w/rappvision-repair-manual
family: rappvision
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 8bdced4d557cb1aeba73c549429060af9c4bc96f
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rappvision-repair-manual: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappvision-repair-manual.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappvision-repair-manual` at `8bdced4d55`](https://github.com/kody-w/rappvision-repair-manual/tree/8bdced4d557cb1aeba73c549429060af9c4bc96f) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7db54d9ec4fbefafe83d852c89674cde926e7f07d0aaf2799ea0237d3b48a50d`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappvision-repair-manual` at `8bdced4d55` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappvision-repair-manual --json` from the folder that holds both.
