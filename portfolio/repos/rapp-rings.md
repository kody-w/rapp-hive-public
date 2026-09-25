---
repo: kody-w/rapp-rings
family: grail
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 4eb4fcace7f70d5af3d0d0e8d47c0db8498bd8b9
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-rings: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-rings.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-rings` at `4eb4fcace7`](https://github.com/kody-w/rapp-rings/tree/4eb4fcace7f70d5af3d0d0e8d47c0db8498bd8b9) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `77b3d5806a543d2b6d8189a957b7bbdf0936ffb115049f5acfc2db5075941065`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-rings` at `4eb4fcace7` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-rings --json` from the folder that holds both.
