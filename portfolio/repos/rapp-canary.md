---
repo: kody-w/rapp-canary
family: release-channels
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 7ac5c778b43337909ed439c5e954bdc8f4460b7c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 20
header: missing
---

# rapp-canary: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-canary.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/rapp-canary` at `7ac5c778b4`](https://github.com/kody-w/rapp-canary/tree/7ac5c778b43337909ed439c5e954bdc8f4460b7c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 2 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `1328d38e8f8a6f7d122f28dc444ab69e60f6b1438fe51c04302eefa8c2a40cca`.
- "experimental" mentions: 20 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-canary` at `7ac5c778b4` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-canary --json` from the folder that holds both.
