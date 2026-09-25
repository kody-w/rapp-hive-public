---
repo: kody-w/sentinel
family: rapp-related
wave: 2
status: certified
verdict: CLEAN
evidence_commit: d62e7a666b9d9418e0a4ce64cca04fd0de153335
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# sentinel: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/sentinel.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/sentinel` at `d62e7a666b`](https://github.com/kody-w/sentinel/tree/d62e7a666b9d9418e0a4ce64cca04fd0de153335).

- Evidence: [`kody-w/sentinel` at `d62e7a666b`](https://github.com/kody-w/sentinel/tree/d62e7a666b9d9418e0a4ce64cca04fd0de153335) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `55d4b74d9b0f1a1c3027ff5df5cd8ce77251998a419ddd8a9dfc249fa049d601`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/sentinel` at `d62e7a666b` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py sentinel --json` from the folder that holds both.
