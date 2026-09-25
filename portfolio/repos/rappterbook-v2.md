---
repo: kody-w/rappterbook-v2
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: ed4a91faa1dd1ebf275a97966110a8e4b1c8828f
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rappterbook-v2: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbook-v2.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappterbook-v2` at `ed4a91faa1`](https://github.com/kody-w/rappterbook-v2/tree/ed4a91faa1dd1ebf275a97966110a8e4b1c8828f) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7e795dd3e054d68976fc811e9fc3873a692a7be89b8d69254acd5e48b9cf35ff`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rappterbook-v2` at `ed4a91faa1` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbook-v2 --json` from the folder that holds both.
