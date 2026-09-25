---
repo: kody-w/leviathan
family: brainstem
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 42d02ad1b041b328540b30d54c7b2a68b9d961aa
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# leviathan: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/leviathan.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/leviathan` at `42d02ad1b0`](https://github.com/kody-w/leviathan/tree/42d02ad1b041b328540b30d54c7b2a68b9d961aa) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `366570e0fd267e381e81e7e78c9bb56bdf42ade0a23908477907b362ef59c428`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/leviathan` at `42d02ad1b0` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py leviathan --json` from the folder that holds both.
