---
repo: kody-w/RAPP_Desktop
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 0aea2ecf7e66ebffb30d3af6a550eac638356292
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# RAPP_Desktop: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP_Desktop.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/RAPP_Desktop` at `0aea2ecf7e`](https://github.com/kody-w/RAPP_Desktop/tree/0aea2ecf7e66ebffb30d3af6a550eac638356292) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a7b688ff8510cb9a6793fd3572f2dd77b2f0fb1a73c4dcc49330a42335803f6e`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/RAPP_Desktop` at `0aea2ecf7e` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP_Desktop --json` from the folder that holds both.
