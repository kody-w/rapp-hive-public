---
repo: kody-w/rapp-cortex
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 63101ef2d9f85c2a19445204123077ac14e5bb86
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-cortex: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-cortex.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-cortex` at `63101ef2d9`](https://github.com/kody-w/rapp-cortex/tree/63101ef2d9f85c2a19445204123077ac14e5bb86) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `22298a3e1559322aa1ada572db1a06d35d57011ebd64b2055872bf3d589872c3`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-cortex` at `63101ef2d9` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-cortex --json` from the folder that holds both.
