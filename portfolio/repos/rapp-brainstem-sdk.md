---
repo: kody-w/rapp-brainstem-sdk
family: brainstem
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 418fd69d76e8fc6a494782b669560f4212292fb5
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-brainstem-sdk: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-brainstem-sdk.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-brainstem-sdk` at `418fd69d76`](https://github.com/kody-w/rapp-brainstem-sdk/tree/418fd69d76e8fc6a494782b669560f4212292fb5) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `4e2dd54742eed36dc773f8a0012f242355e2dfdd48d0f9bb886cee7d87457a42`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-brainstem-sdk` at `418fd69d76` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-brainstem-sdk --json` from the folder that holds both.
