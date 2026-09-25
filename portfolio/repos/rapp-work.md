---
repo: kody-w/rapp-work
family: rapp1-core
wave: 1
status: certified
verdict: COMPLIANT
evidence_commit: 29ead23b21645f8d7682ee00414930ffa9ce0ca6
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: pr-open
header_pr: https://github.com/kody-w/rapp-work/pull/3
---

# rapp-work: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-work.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/rapp-work` at `29ead23b21`](https://github.com/kody-w/rapp-work/tree/29ead23b21645f8d7682ee00414930ffa9ce0ca6) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `7077263db5435c026db9c50353292240f116308bac08afe6ba8a3012134395cb`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/rapp-work/pull/3).

## Check it yourself

Clone `kody-w/rapp-work` at `29ead23b21` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-work --json` from the folder that holds both.
