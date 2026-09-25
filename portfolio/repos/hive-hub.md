---
repo: kody-w/hive-hub
family: hive
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 1db94d2b1b5d9d4fb6f9d2865c3a2fe543875c31
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 5
header: missing
---

# hive-hub: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/hive-hub.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/hive-hub` at `1db94d2b1b`](https://github.com/kody-w/hive-hub/tree/1db94d2b1b5d9d4fb6f9d2865c3a2fe543875c31).

- Evidence: [`kody-w/hive-hub` at `1db94d2b1b`](https://github.com/kody-w/hive-hub/tree/1db94d2b1b5d9d4fb6f9d2865c3a2fe543875c31) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `3c1a8f19436ce7f8cb819da088d7c72f2cc29ff7213fe9c47bcdf6c574eff1db`.
- "experimental" mentions: 5 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/hive-hub` at `1db94d2b1b` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py hive-hub --json` from the folder that holds both.
