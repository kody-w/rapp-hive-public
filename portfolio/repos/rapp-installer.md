---
repo: kody-w/rapp-installer
family: rapp1-core
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 49db80c8c6b6caa7647369beaf477d374a8f293c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 11
header: missing
---

# rapp-installer: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-installer.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-installer` at `49db80c8c6`](https://github.com/kody-w/rapp-installer/tree/49db80c8c6b6caa7647369beaf477d374a8f293c).

- Evidence: [`kody-w/rapp-installer` at `49db80c8c6`](https://github.com/kody-w/rapp-installer/tree/49db80c8c6b6caa7647369beaf477d374a8f293c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `cc5f82f00d3b6c37e663e985ab947441b5460d676ab2bfd6e6104f2ea571f6b3`.
- "experimental" mentions: 11 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-installer` at `49db80c8c6` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-installer --json` from the folder that holds both.
