---
repo: kody-w/rapp-coop
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: d71893259a0ba23c5bd81bf157260cf662ddf198
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-coop: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-coop.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-coop` at `d71893259a`](https://github.com/kody-w/rapp-coop/tree/d71893259a0ba23c5bd81bf157260cf662ddf198) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7af81504deb5f4b5c0dace00cda6f26101c32e08b9ec0fcd60b6a5d18c5cb6e1`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-coop` at `d71893259a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-coop --json` from the folder that holds both.
