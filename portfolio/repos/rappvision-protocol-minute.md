---
repo: kody-w/rappvision-protocol-minute
family: rappvision
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 0a72c43d84e9eb3549fca14c0e6bf672bbe1bdd2
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rappvision-protocol-minute: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappvision-protocol-minute.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappvision-protocol-minute` at `0a72c43d84`](https://github.com/kody-w/rappvision-protocol-minute/tree/0a72c43d84e9eb3549fca14c0e6bf672bbe1bdd2) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `75da5c65ff089bbc431f3e51e75caaff3041dbf86d32a38952e2fc0cdb6d2571`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappvision-protocol-minute` at `0a72c43d84` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappvision-protocol-minute --json` from the folder that holds both.
