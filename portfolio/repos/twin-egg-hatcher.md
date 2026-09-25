---
repo: kody-w/twin-egg-hatcher
family: twins
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 6e96a7ed24b3f70a8568543510792236d5a53a8d
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# twin-egg-hatcher: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/twin-egg-hatcher.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/twin-egg-hatcher` at `6e96a7ed24`](https://github.com/kody-w/twin-egg-hatcher/tree/6e96a7ed24b3f70a8568543510792236d5a53a8d) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `3f38f4b663c089560b4d8e020b7a8e090e07a108107370f962fa85fce46fdb18`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/twin-egg-hatcher` at `6e96a7ed24` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py twin-egg-hatcher --json` from the folder that holds both.
