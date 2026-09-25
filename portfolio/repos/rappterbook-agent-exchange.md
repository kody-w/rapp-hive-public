---
repo: kody-w/rappterbook-agent-exchange
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: ff0f726013c974cabcb2b021e75d69b80faa508b
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 4
header: missing
---

# rappterbook-agent-exchange: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbook-agent-exchange.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappterbook-agent-exchange` at `ff0f726013`](https://github.com/kody-w/rappterbook-agent-exchange/tree/ff0f726013c974cabcb2b021e75d69b80faa508b) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `d7e3d26a5926f27e41ee9d8c8d130d700acb65b33240d565a7ff1a95ad9dd6e2`.
- "experimental" mentions: 4 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappterbook-agent-exchange` at `ff0f726013` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbook-agent-exchange --json` from the folder that holds both.
