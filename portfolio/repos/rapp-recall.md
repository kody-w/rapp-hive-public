---
repo: kody-w/rapp-recall
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: cfd5491d60746496b2a04e4f15529f14fa959148
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 30
header: missing
---

# rapp-recall: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-recall.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-recall` at `cfd5491d60`](https://github.com/kody-w/rapp-recall/tree/cfd5491d60746496b2a04e4f15529f14fa959148).

- Evidence: [`kody-w/rapp-recall` at `cfd5491d60`](https://github.com/kody-w/rapp-recall/tree/cfd5491d60746496b2a04e4f15529f14fa959148) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `30a4811a2f40a32466c6fdbd41ebec759ec47b890ad1ae4532ec4700114bdfc9`.
- "experimental" mentions: 30 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-recall` at `cfd5491d60` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-recall --json` from the folder that holds both.
