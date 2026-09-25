---
repo: kody-w/rapp-light
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 01a7e1b444ef3269836036a63f291223eb132bc0
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 5
header: missing
---

# rapp-light: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-light.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-light` at `01a7e1b444`](https://github.com/kody-w/rapp-light/tree/01a7e1b444ef3269836036a63f291223eb132bc0) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `699b6a02c8268f88b90b23fc2be8bbb992372e940316676750adfdb17c839001`.
- "experimental" mentions: 5 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-light` at `01a7e1b444` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-light --json` from the folder that holds both.
