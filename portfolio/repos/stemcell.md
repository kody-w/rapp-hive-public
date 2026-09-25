---
repo: kody-w/stemcell
family: brainstem
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 7cc90dd25a395d9feb3bb3e1efeafdbcee62acce
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 6
header: missing
---

# stemcell: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/stemcell.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/stemcell` at `7cc90dd25a`](https://github.com/kody-w/stemcell/tree/7cc90dd25a395d9feb3bb3e1efeafdbcee62acce) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `b9581c1928b98f65e9bc3382e03d9ef7163af4effc025000d031b49270cdd7f2`.
- "experimental" mentions: 6 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/stemcell` at `7cc90dd25a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py stemcell --json` from the folder that holds both.
