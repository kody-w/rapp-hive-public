---
repo: kody-w/rapp-heir
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 58362a43bbf02d3909aacb6617b745f0fca8d0ad
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 3
header: missing
---

# rapp-heir: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-heir.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-heir` at `58362a43bb`](https://github.com/kody-w/rapp-heir/tree/58362a43bbf02d3909aacb6617b745f0fca8d0ad) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f130c7c4365580d96e0f1858c92c92092b80e1841fe9bf1014379713b8bd7a8c`.
- "experimental" mentions: 3 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-heir` at `58362a43bb` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-heir --json` from the folder that holds both.
