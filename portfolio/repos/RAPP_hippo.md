---
repo: kody-w/RAPP_hippo
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: c55d62315104540f859a9e9db6d14fc385739f8e
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 9
header: missing
---

# RAPP_hippo: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP_hippo.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/RAPP_hippo` at `c55d623151`](https://github.com/kody-w/RAPP_hippo/tree/c55d62315104540f859a9e9db6d14fc385739f8e) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `c378d83e4b6167b58dca8fdb36a7a228935988e5f4f73f38dc6bb2cc0e1f6a10`.
- "experimental" mentions: 9 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/RAPP_hippo` at `c55d623151` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP_hippo --json` from the folder that holds both.
