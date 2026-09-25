---
repo: kody-w/rapp-brainfreeze
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: d7d816c0768ef108e1a654a8d03669f0b0ba1885
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# rapp-brainfreeze: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-brainfreeze.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-brainfreeze` at `d7d816c076`](https://github.com/kody-w/rapp-brainfreeze/tree/d7d816c0768ef108e1a654a8d03669f0b0ba1885) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `8aa85cede4631411cd7168ac4c9fecd53678cce829577b9bc2236cd3223e9045`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-brainfreeze` at `d7d816c076` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-brainfreeze --json` from the folder that holds both.
