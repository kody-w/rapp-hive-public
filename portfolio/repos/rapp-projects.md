---
repo: kody-w/rapp-projects
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 2b375029d051b80b4df8c19749aeb64a96df216a
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-projects: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-projects.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-projects` at `2b375029d0`](https://github.com/kody-w/rapp-projects/tree/2b375029d051b80b4df8c19749aeb64a96df216a) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `87bee3ccbfd8e87909dabb253b86d89f7b090de9ec384cb16baf68aa398023eb`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-projects` at `2b375029d0` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-projects --json` from the folder that holds both.
