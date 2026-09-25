---
repo: kody-w/RAPP-Network
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: a22f3f2be9bfc5b311b2e3956069779cd10f42ef
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# RAPP-Network: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP-Network.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/RAPP-Network` at `a22f3f2be9`](https://github.com/kody-w/RAPP-Network/tree/a22f3f2be9bfc5b311b2e3956069779cd10f42ef) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `429ce617ec45dd8092b702df9a57f943c619aa8a56ea9775de12d3059ecf2db1`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/RAPP-Network` at `a22f3f2be9` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP-Network --json` from the folder that holds both.
