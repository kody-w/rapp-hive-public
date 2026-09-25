---
repo: kody-w/rapp-fps
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 9eacce9b365023d8a803533d63c5f1e1a73e2bbb
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rapp-fps: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-fps.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-fps` at `9eacce9b36`](https://github.com/kody-w/rapp-fps/tree/9eacce9b365023d8a803533d63c5f1e1a73e2bbb) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `2f4b57bbaa093274e2cccbccf7c5e175f1a22967edd91055cc15ba6aeca6c134`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rapp-fps` at `9eacce9b36` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-fps --json` from the folder that holds both.
