---
repo: kody-w/rapp-wiki-observatory
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: ccccb5c786e8ae4e7123c39289bab367ad11a24d
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-wiki-observatory: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-wiki-observatory.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-wiki-observatory` at `ccccb5c786`](https://github.com/kody-w/rapp-wiki-observatory/tree/ccccb5c786e8ae4e7123c39289bab367ad11a24d) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `86132d970403b6afe65241a8f2faf6831556cd08cd58135a55778540622479e0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-wiki-observatory` at `ccccb5c786` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-wiki-observatory --json` from the folder that holds both.
