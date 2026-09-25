---
repo: kody-w/rappter-mmo
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 757291f589d31a466923dcc96185b3662f750435
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rappter-mmo: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappter-mmo.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappter-mmo` at `757291f589`](https://github.com/kody-w/rappter-mmo/tree/757291f589d31a466923dcc96185b3662f750435) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `022da5ff88afc4f74ea8de9e737dba1b4e13a8573f9681f860a72617d38ab9a0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rappter-mmo` at `757291f589` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappter-mmo --json` from the folder that holds both.
