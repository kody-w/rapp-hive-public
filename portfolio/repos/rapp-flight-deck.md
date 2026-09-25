---
repo: kody-w/rapp-flight-deck
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: f33f26514fa65e7fc7ab1ebd3711de53b0e8c7e7
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-flight-deck: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-flight-deck.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-flight-deck` at `f33f26514f`](https://github.com/kody-w/rapp-flight-deck/tree/f33f26514fa65e7fc7ab1ebd3711de53b0e8c7e7) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f3ff99562b0c2a4eb18b4f49d42876ee6b3fd7aced398ad9f37f8323bfa911a5`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-flight-deck` at `f33f26514f` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-flight-deck --json` from the folder that holds both.
