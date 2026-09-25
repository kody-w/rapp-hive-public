---
repo: kody-w/rapp-installer-dev
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 2deafaec170e718a71a7ffe1d5f2237bb5b31ca8
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 8
header: missing
---

# rapp-installer-dev: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-installer-dev.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-installer-dev` at `2deafaec17`](https://github.com/kody-w/rapp-installer-dev/tree/2deafaec170e718a71a7ffe1d5f2237bb5b31ca8).

- Evidence: [`kody-w/rapp-installer-dev` at `2deafaec17`](https://github.com/kody-w/rapp-installer-dev/tree/2deafaec170e718a71a7ffe1d5f2237bb5b31ca8) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `d237bb164f4f2b3d4bf3ab1fe15231e6c1c1e29413f5e226072633a9e86ca349`.
- "experimental" mentions: 8 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-installer-dev` at `2deafaec17` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-installer-dev --json` from the folder that holds both.
