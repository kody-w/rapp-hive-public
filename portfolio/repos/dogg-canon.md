---
repo: kody-w/dogg-canon
family: dogg-network
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 7bdae25ed8bdf0a6aa48789d9136c5ab4caca5e4
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# dogg-canon: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/dogg-canon.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/dogg-canon` at `7bdae25ed8`](https://github.com/kody-w/dogg-canon/tree/7bdae25ed8bdf0a6aa48789d9136c5ab4caca5e4) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 32 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a224beed937cff06aeeb9bac91f121d9684ce20572c88226722430cdfd4e69e6`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/dogg-canon` at `7bdae25ed8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py dogg-canon --json` from the folder that holds both.
