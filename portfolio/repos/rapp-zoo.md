---
repo: kody-w/rapp-zoo
family: rapp-projects
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 7a0eeb9c647feac1e0aa27ee662442a3a4929339
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 3
header: missing
---

# rapp-zoo: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-zoo.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/rapp-zoo` at `7a0eeb9c64`](https://github.com/kody-w/rapp-zoo/tree/7a0eeb9c647feac1e0aa27ee662442a3a4929339) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 5 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `3aa73b8ef743e651d67a88fcddbc2d26ec286bebdb21e8775ab5c0263865e63f`.
- "experimental" mentions: 3 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-zoo` at `7a0eeb9c64` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-zoo --json` from the folder that holds both.
