---
repo: kody-w/rapp-imessage-launchpad
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: f0b57ff70f3acdd8d8f56e8a33d0c8fe6b960b62
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-imessage-launchpad: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-imessage-launchpad.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-imessage-launchpad` at `f0b57ff70f`](https://github.com/kody-w/rapp-imessage-launchpad/tree/f0b57ff70f3acdd8d8f56e8a33d0c8fe6b960b62) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `2b939c7d1cf3a3d6aad19b5e9705c3d5f864eab7f01ac7bed32e5a02c277d76f`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-imessage-launchpad` at `f0b57ff70f` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-imessage-launchpad --json` from the folder that holds both.
