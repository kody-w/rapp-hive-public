---
repo: kody-w/rapp-sentinel
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: eebfa42dc8222a602d24d16c67e335955c6e7de2
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-sentinel: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-sentinel.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-sentinel` at `eebfa42dc8`](https://github.com/kody-w/rapp-sentinel/tree/eebfa42dc8222a602d24d16c67e335955c6e7de2).

- Evidence: [`kody-w/rapp-sentinel` at `eebfa42dc8`](https://github.com/kody-w/rapp-sentinel/tree/eebfa42dc8222a602d24d16c67e335955c6e7de2) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ed5680a1db0aba4cf17b75edec433d01c98c3992bbbe5d5882fb4addbc44455a`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-sentinel` at `eebfa42dc8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-sentinel --json` from the folder that holds both.
