---
repo: kody-w/rapp-kited-twin
family: twins
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 9f844ec5e8a148b5a17e1080e9a715feea954e5b
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-kited-twin: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-kited-twin.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-kited-twin` at `9f844ec5e8`](https://github.com/kody-w/rapp-kited-twin/tree/9f844ec5e8a148b5a17e1080e9a715feea954e5b) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `5b52a4054e7997e369cb496beb4c1c54e42bfc667e4f398de55f67f87be8ec5c`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-kited-twin` at `9f844ec5e8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-kited-twin --json` from the folder that holds both.
