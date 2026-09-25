---
repo: kody-w/rapp-keyring
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 89386724e9bf8b365ce3bd2847fbcc06365953d5
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-keyring: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-keyring.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-keyring` at `89386724e9`](https://github.com/kody-w/rapp-keyring/tree/89386724e9bf8b365ce3bd2847fbcc06365953d5) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `cbeec080845a605eac7628a023f99b8ef171d3c73e0d8baafd38732d55569e00`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-keyring` at `89386724e9` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-keyring --json` from the folder that holds both.
