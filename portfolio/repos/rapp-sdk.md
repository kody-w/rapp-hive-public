---
repo: kody-w/rapp-sdk
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 402a7e0210b2c4e71d0a1b44744b842f3c2d6b49
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 27
header: missing
---

# rapp-sdk: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-sdk.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-sdk` at `402a7e0210`](https://github.com/kody-w/rapp-sdk/tree/402a7e0210b2c4e71d0a1b44744b842f3c2d6b49) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a392c7cad5a5fe809721e59ea91c19f9d42126a410efe172efb248c3c0d50e7c`.
- "experimental" mentions: 27 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-sdk` at `402a7e0210` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-sdk --json` from the folder that holds both.
