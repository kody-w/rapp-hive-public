---
repo: kody-w/rappterverse
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 6819ad75ed1da517f2099fc6d3db18b7d045b2cf
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rappterverse: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterverse.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappterverse` at `6819ad75ed`](https://github.com/kody-w/rappterverse/tree/6819ad75ed1da517f2099fc6d3db18b7d045b2cf) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `0df92430011157f12c04f3b94b19087abfd18e8e9155c97abfe89eb78e9a22aa`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappterverse` at `6819ad75ed` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterverse --json` from the folder that holds both.
