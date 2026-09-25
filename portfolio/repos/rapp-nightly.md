---
repo: kody-w/rapp-nightly
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 27d62617a1d805d5648c0827c4d863359f307efe
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 12
header: missing
---

# rapp-nightly: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-nightly.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-nightly` at `27d62617a1`](https://github.com/kody-w/rapp-nightly/tree/27d62617a1d805d5648c0827c4d863359f307efe).

- Evidence: [`kody-w/rapp-nightly` at `27d62617a1`](https://github.com/kody-w/rapp-nightly/tree/27d62617a1d805d5648c0827c4d863359f307efe) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7d470ca2787223a225b248139e453cbf6fce8e71556a81c8002a414f842e6e9b`.
- "experimental" mentions: 12 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-nightly` at `27d62617a1` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-nightly --json` from the folder that holds both.
