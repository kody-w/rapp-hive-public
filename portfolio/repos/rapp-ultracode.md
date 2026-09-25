---
repo: kody-w/rapp-ultracode
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: f27181f221c1c760128fd7dd3ae2a25b1e778202
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# rapp-ultracode: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-ultracode.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-ultracode` at `f27181f221`](https://github.com/kody-w/rapp-ultracode/tree/f27181f221c1c760128fd7dd3ae2a25b1e778202) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `20f84391ba7e751f215ed151a4d4d19e8340093d2e2be4ed72fb17c0e921ac8c`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-ultracode` at `f27181f221` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-ultracode --json` from the folder that holds both.
