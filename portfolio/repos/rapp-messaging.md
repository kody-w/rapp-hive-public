---
repo: kody-w/rapp-messaging
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 0586678530bb16215f91104a11737bc69c6f0c48
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-messaging: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-messaging.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-messaging` at `0586678530`](https://github.com/kody-w/rapp-messaging/tree/0586678530bb16215f91104a11737bc69c6f0c48) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `895f3a3b860e89844a6f20dc828584f51b979ae2a199cf9300cc3f4a82462a65`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-messaging` at `0586678530` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-messaging --json` from the folder that holds both.
