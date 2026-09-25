---
repo: kody-w/rapp-mission
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 93e2514437ceecf4212fc6a6f05d12786fc432b7
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-mission: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-mission.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-mission` at `93e2514437`](https://github.com/kody-w/rapp-mission/tree/93e2514437ceecf4212fc6a6f05d12786fc432b7) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `0d43881b94ad5b43f561fd3c7cf0d9770517c49a4f876281349707e6f2f80070`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-mission` at `93e2514437` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-mission --json` from the folder that holds both.
