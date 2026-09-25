---
repo: kody-w/RAPP_Hub
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 00ac2f73cade3f64c39359e9a90fca636bc387aa
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# RAPP_Hub: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP_Hub.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/RAPP_Hub` at `00ac2f73ca`](https://github.com/kody-w/RAPP_Hub/tree/00ac2f73cade3f64c39359e9a90fca636bc387aa) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `8ccd9a53f724cd3c6093d0139de0ae3c3bee27c5495a31052d31a27496a31cf6`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/RAPP_Hub` at `00ac2f73ca` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP_Hub --json` from the folder that holds both.
