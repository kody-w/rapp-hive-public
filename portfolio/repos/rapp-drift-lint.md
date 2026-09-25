---
repo: kody-w/rapp-drift-lint
family: rapp1-core
wave: 1
status: certified
verdict: CLEAN
evidence_commit: de1c664154d3456224bdf95e830736ffb5270c2b
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: pr-open
header_pr: https://github.com/kody-w/rapp-drift-lint/pull/2
---

# rapp-drift-lint: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-drift-lint.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-drift-lint` at `de1c664154`](https://github.com/kody-w/rapp-drift-lint/tree/de1c664154d3456224bdf95e830736ffb5270c2b) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `bd2fbdb226333db8a5a33dcb8339cb4d54c6a1050949ec15674a367effcff571`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/rapp-drift-lint/pull/2).

## Check it yourself

Clone `kody-w/rapp-drift-lint` at `de1c664154` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-drift-lint --json` from the folder that holds both.
