---
repo: kody-w/lisppy
family: rapp1-core
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 5e3a2e3275825ffecdbc4b12541aff48d7ff235e
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: pr-open
header_pr: https://github.com/kody-w/lisppy/pull/1
---

# lisppy: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/lisppy.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/lisppy` at `5e3a2e3275`](https://github.com/kody-w/lisppy/tree/5e3a2e3275825ffecdbc4b12541aff48d7ff235e) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `4b8b8bd0ac6781a6356fc3df65bf70ee8d2ba2fd0cb846010516c1844e7b9c44`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/lisppy/pull/1).

## Check it yourself

Clone `kody-w/lisppy` at `5e3a2e3275` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py lisppy --json` from the folder that holds both.
