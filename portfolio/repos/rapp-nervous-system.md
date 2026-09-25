---
repo: kody-w/rapp-nervous-system
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 4068ccf75f55d1736c264f68ee215af8d2f72daf
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-nervous-system: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-nervous-system.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-nervous-system` at `4068ccf75f`](https://github.com/kody-w/rapp-nervous-system/tree/4068ccf75f55d1736c264f68ee215af8d2f72daf) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `dfa3b5e4fa825217fa029e574c090bc8755142f3deef9b75e9ef72f8e27b34d7`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-nervous-system` at `4068ccf75f` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-nervous-system --json` from the folder that holds both.
