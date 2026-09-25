---
repo: kody-w/hive-showcase
family: hive
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 331fb28f09b203ef3671d9d18ac3c4e1689a5198
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 7
header: missing
---

# hive-showcase: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/hive-showcase.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/hive-showcase` at `331fb28f09`](https://github.com/kody-w/hive-showcase/tree/331fb28f09b203ef3671d9d18ac3c4e1689a5198) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a913c50a8ed4212715c0bc5edafaa6a773c954c5095b28354950a3c529e78f28`.
- "experimental" mentions: 7 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/hive-showcase` at `331fb28f09` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py hive-showcase --json` from the folder that holds both.
