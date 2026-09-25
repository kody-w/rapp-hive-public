---
repo: kody-w/rapp-spine
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: b21ebe12b274c4404af916944f808303e7005a89
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-spine: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-spine.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-spine` at `b21ebe12b2`](https://github.com/kody-w/rapp-spine/tree/b21ebe12b274c4404af916944f808303e7005a89) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `5422ecc643866b754ceee3e31ece88d3f95a6e4883c5f2a37446d75abb0af7bf`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-spine` at `b21ebe12b2` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-spine --json` from the folder that holds both.
