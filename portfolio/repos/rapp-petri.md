---
repo: kody-w/rapp-petri
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: b1f953c9cb498eb13fa0da07d94f065f0664d782
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-petri: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-petri.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-petri` at `b1f953c9cb`](https://github.com/kody-w/rapp-petri/tree/b1f953c9cb498eb13fa0da07d94f065f0664d782) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `824b8bf9d6da05efafaa8be8f39b939cd63cf85588ae916fa66928e6307ba120`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-petri` at `b1f953c9cb` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-petri --json` from the folder that holds both.
