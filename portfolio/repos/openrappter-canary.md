---
repo: kody-w/openrappter-canary
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: a86599c12e9bf8f466f601e004b95723abc25dfd
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# openrappter-canary: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/openrappter-canary.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/openrappter-canary` at `a86599c12e`](https://github.com/kody-w/openrappter-canary/tree/a86599c12e9bf8f466f601e004b95723abc25dfd) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `c4c1f11dc33eca6df6e294194f23a34a9df44c5f0d9317d57e22cf98349f0e0d`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/openrappter-canary` at `a86599c12e` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py openrappter-canary --json` from the folder that holds both.
