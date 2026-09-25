---
repo: kody-w/rapp-hive-hub-join
family: hive
wave: 1
status: certified
verdict: CLEAN
evidence_commit: d99fc58f30a282d11a32b97ab820cf4690ee9a1a
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: pr-open
header_pr: https://github.com/kody-w/rapp-hive-hub-join/pull/1
---

# rapp-hive-hub-join: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-hive-hub-join.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-hive-hub-join` at `d99fc58f30`](https://github.com/kody-w/rapp-hive-hub-join/tree/d99fc58f30a282d11a32b97ab820cf4690ee9a1a) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `3d2b10e20b8ebaac91eaf915af2828613bcb9a629ef626a9dd695696dc2d98e0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/rapp-hive-hub-join/pull/1).

## Check it yourself

Clone `kody-w/rapp-hive-hub-join` at `d99fc58f30` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-hive-hub-join --json` from the folder that holds both.
