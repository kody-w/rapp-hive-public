---
repo: kody-w/rapp-remix
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 04cb6f56ab05e00fe54880e4631a27093a5651ad
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-remix: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-remix.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-remix` at `04cb6f56ab`](https://github.com/kody-w/rapp-remix/tree/04cb6f56ab05e00fe54880e4631a27093a5651ad) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `57ea6aaa640f60f3022c08400ef13a3fcdd32e43656596560ee752f1cf4b8e2c`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-remix` at `04cb6f56ab` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-remix --json` from the folder that holds both.
