---
repo: kody-w/rappter-cli
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: c7b919357a201489ba3ecaae83cb56386eb15ea9
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rappter-cli: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappter-cli.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappter-cli` at `c7b919357a`](https://github.com/kody-w/rappter-cli/tree/c7b919357a201489ba3ecaae83cb56386eb15ea9) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `08e825e5cb194e748aafa3708f0a2724617d7aaa2bed21dc2f543ff2694f8a8f`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappter-cli` at `c7b919357a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappter-cli --json` from the folder that holds both.
