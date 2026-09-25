---
repo: kody-w/vneighborhood-research-lab
family: neighborhoods
wave: 2
status: certified
verdict: CLEAN
evidence_commit: ba9413e42a87a35f51f5cff235f495ca31f00328
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# vneighborhood-research-lab: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/vneighborhood-research-lab.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/vneighborhood-research-lab` at `ba9413e42a`](https://github.com/kody-w/vneighborhood-research-lab/tree/ba9413e42a87a35f51f5cff235f495ca31f00328) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `9cf7c2bb0ef3f32ba3f10b98a27b12ca6f1d572f9a257a7f3cd03ace48d7b0f0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/vneighborhood-research-lab` at `ba9413e42a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py vneighborhood-research-lab --json` from the folder that holds both.
