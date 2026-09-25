---
repo: kody-w/rapp-estate
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: acc17dca283619f288274f237c8c61f437d014f3
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rapp-estate: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-estate.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-estate` at `acc17dca28`](https://github.com/kody-w/rapp-estate/tree/acc17dca283619f288274f237c8c61f437d014f3) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ca85fef0127ec6c837305cdb1c51befeb51aa7e6cdf1d974800ae579178e0d5f`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rapp-estate` at `acc17dca28` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-estate --json` from the folder that holds both.
