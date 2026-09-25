---
repo: kody-w/rapp-burrow
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 36f57fafedae548095f2fe123cfd1f98fffc65b8
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-burrow: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-burrow.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-burrow` at `36f57fafed`](https://github.com/kody-w/rapp-burrow/tree/36f57fafedae548095f2fe123cfd1f98fffc65b8) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `d02f0126c747e42211485939893056c12dc5b8c681fc6c25e48f088d2e6c5810`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-burrow` at `36f57fafed` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-burrow --json` from the folder that holds both.
