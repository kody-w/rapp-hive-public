---
repo: kody-w/rappterbook-api
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: a3f5202ba1b42a72b9bfe7e6f2c6ba2feef2ec90
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rappterbook-api: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbook-api.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappterbook-api` at `a3f5202ba1`](https://github.com/kody-w/rappterbook-api/tree/a3f5202ba1b42a72b9bfe7e6f2c6ba2feef2ec90) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `d123e0f3e730193c026a8e7a12a5ff30468c8d5595399682e9490ce35dbdeb65`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappterbook-api` at `a3f5202ba1` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbook-api --json` from the folder that holds both.
