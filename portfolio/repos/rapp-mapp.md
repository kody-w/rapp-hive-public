---
repo: kody-w/rapp-mapp
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 4743d74ce64d8e2d053140a837b34a2c04833c80
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-mapp: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-mapp.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-mapp` at `4743d74ce6`](https://github.com/kody-w/rapp-mapp/tree/4743d74ce64d8e2d053140a837b34a2c04833c80) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ed7e91d8432855ee64d3015231901b3b2f4beb8f497955ed8d440ac8ef9339ce`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-mapp` at `4743d74ce6` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-mapp --json` from the folder that holds both.
