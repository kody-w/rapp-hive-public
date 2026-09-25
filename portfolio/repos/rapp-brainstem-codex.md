---
repo: kody-w/rapp-brainstem-codex
family: brainstem
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 34364fb1428813dc9ed16e1637187b4b231ebbf1
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-brainstem-codex: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-brainstem-codex.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-brainstem-codex` at `34364fb142`](https://github.com/kody-w/rapp-brainstem-codex/tree/34364fb1428813dc9ed16e1637187b4b231ebbf1) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `116b7b4c0ce0fc3f5776ef7e30f04ec24440d2af763297e1b29a9b6dc808e6a9`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-brainstem-codex` at `34364fb142` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-brainstem-codex --json` from the folder that holds both.
