---
repo: kody-w/rapp-installer-canary
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 8bb6b75d2cfc0227bfd69e0995a308e4f2309cdc
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 7
header: missing
---

# rapp-installer-canary: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-installer-canary.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-installer-canary` at `8bb6b75d2c`](https://github.com/kody-w/rapp-installer-canary/tree/8bb6b75d2cfc0227bfd69e0995a308e4f2309cdc) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ccd3154160bbc4447d8772c332bb13dff1528714f51fc9fae60535c7dd1d48ca`.
- "experimental" mentions: 7 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-installer-canary` at `8bb6b75d2c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-installer-canary --json` from the folder that holds both.
