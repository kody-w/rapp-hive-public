---
repo: kody-w/rapp-beta
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 562b5e18f0e6f9dd63d95d8691c3ed1e9afabd52
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 12
header: missing
---

# rapp-beta: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-beta.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-beta` at `562b5e18f0`](https://github.com/kody-w/rapp-beta/tree/562b5e18f0e6f9dd63d95d8691c3ed1e9afabd52).

- Evidence: [`kody-w/rapp-beta` at `562b5e18f0`](https://github.com/kody-w/rapp-beta/tree/562b5e18f0e6f9dd63d95d8691c3ed1e9afabd52) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ef5bb34075a7a0b8d8313f225571ed2b8e06df912adffe5672eae0bbadc6b8ca`.
- "experimental" mentions: 12 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-beta` at `562b5e18f0` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-beta --json` from the folder that holds both.
