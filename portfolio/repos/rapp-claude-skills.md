---
repo: kody-w/rapp-claude-skills
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: d675bf06c4b51232833fb426ddcb7bc4079b4b6c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-claude-skills: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-claude-skills.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-claude-skills` at `d675bf06c4`](https://github.com/kody-w/rapp-claude-skills/tree/d675bf06c4b51232833fb426ddcb7bc4079b4b6c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ae967358d5f98baf4012c1a7ac15e0a70403d57a9fda414704176f4559741601`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-claude-skills` at `d675bf06c4` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-claude-skills --json` from the folder that holds both.
