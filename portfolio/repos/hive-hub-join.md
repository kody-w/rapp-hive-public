---
repo: kody-w/hive-hub-join
family: hive
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 4c7620c8ae5301f65785bfe4a72fcb3254ec5857
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: pr-open
header_pr: https://github.com/kody-w/hive-hub-join/pull/1
---

# hive-hub-join: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/hive-hub-join.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/hive-hub-join` at `4c7620c8ae`](https://github.com/kody-w/hive-hub-join/tree/4c7620c8ae5301f65785bfe4a72fcb3254ec5857) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `c931be31593f03beb291087d7bc8335ed0b96f41ab9b96e296f3cad7e43810e4`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/hive-hub-join/pull/1).

## Check it yourself

Clone `kody-w/hive-hub-join` at `4c7620c8ae` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py hive-hub-join --json` from the folder that holds both.
