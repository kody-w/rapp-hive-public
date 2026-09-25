---
repo: kody-w/rapp-dataverse
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: bd843bba3ba14754ccd85594b3a1ce2b26a4cc74
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-dataverse: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-dataverse.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-dataverse` at `bd843bba3b`](https://github.com/kody-w/rapp-dataverse/tree/bd843bba3ba14754ccd85594b3a1ce2b26a4cc74) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `d4d52037419ffa98adf122a6aea4d4a65253132ae50b4fd47b96e3efcaf3f77e`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-dataverse` at `bd843bba3b` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-dataverse --json` from the folder that holds both.
