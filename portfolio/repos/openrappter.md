---
repo: kody-w/openrappter
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: d8601aa91c10f3330ea10b7fa31382137d981dfd
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# openrappter: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/openrappter.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/openrappter` at `d8601aa91c`](https://github.com/kody-w/openrappter/tree/d8601aa91c10f3330ea10b7fa31382137d981dfd) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `82c06915a0e51916f422eff0c315ab085a1b24cd0dc1e98d8686bf4b33bad2ee`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/openrappter` at `d8601aa91c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py openrappter --json` from the folder that holds both.
