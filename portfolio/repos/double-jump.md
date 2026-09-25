---
repo: kody-w/double-jump
family: brainstem
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 5097b61085f9fbcd5529e58fb487b2152b81e78c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 17
header: missing
---

# double-jump: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/double-jump.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/double-jump` at `5097b61085`](https://github.com/kody-w/double-jump/tree/5097b61085f9fbcd5529e58fb487b2152b81e78c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `765692c1e8d48907c4f5c9bfc0afc3573f64e8176d995cf6e6c208affb06d396`.
- "experimental" mentions: 17 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/double-jump` at `5097b61085` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py double-jump --json` from the folder that holds both.
