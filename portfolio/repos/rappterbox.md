---
repo: kody-w/rappterbox
family: rappter
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 656d12767d461c2e9aab5a695be28f2b247fd187
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 24
header: missing
---

# rappterbox: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbox.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/rappterbox` at `656d12767d`](https://github.com/kody-w/rappterbox/tree/656d12767d461c2e9aab5a695be28f2b247fd187).

- Evidence: [`kody-w/rappterbox` at `656d12767d`](https://github.com/kody-w/rappterbox/tree/656d12767d461c2e9aab5a695be28f2b247fd187) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `9b813d9ef347cb14572eaec77aa1c91c3de663c49619861f7138b3a47850a132`.
- "experimental" mentions: 24 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappterbox` at `656d12767d` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbox --json` from the folder that holds both.
