---
repo: kody-w/rapp-vision-neighborhood
family: neighborhoods
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 2e6c62e77cad7f6b85008c75a4554924b4c6b504
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-vision-neighborhood: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-vision-neighborhood.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-vision-neighborhood` at `2e6c62e77c`](https://github.com/kody-w/rapp-vision-neighborhood/tree/2e6c62e77cad7f6b85008c75a4554924b4c6b504) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f17fc0bb188574714459c80691165880a75cfcb4c62dd1bef31bfbe5c956d923`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-vision-neighborhood` at `2e6c62e77c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-vision-neighborhood --json` from the folder that holds both.
