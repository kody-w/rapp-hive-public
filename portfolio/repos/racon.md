---
repo: kody-w/racon
family: grail
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 2e709f52454f4a7667c09e91c072cce3d0fbb8c7
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# racon: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/racon.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/racon` at `2e709f5245`](https://github.com/kody-w/racon/tree/2e709f52454f4a7667c09e91c072cce3d0fbb8c7) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `e0b5673fe9f285a0c7fac2ea3c265de70ff87888eb4840b53f6ea404b5f4687c`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/racon` at `2e709f5245` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py racon --json` from the folder that holds both.
