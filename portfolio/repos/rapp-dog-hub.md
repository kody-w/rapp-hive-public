---
repo: kody-w/rapp-dog-hub
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 7d7211429b9308839de98150d5f6df764f39c9fe
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rapp-dog-hub: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-dog-hub.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-dog-hub` at `7d7211429b`](https://github.com/kody-w/rapp-dog-hub/tree/7d7211429b9308839de98150d5f6df764f39c9fe) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7d6e859b9aa4a02d0167e90d9835f29b570a5681a5c7af5436c6a55119e215b0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rapp-dog-hub` at `7d7211429b` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-dog-hub --json` from the folder that holds both.
