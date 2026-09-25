---
repo: kody-w/heimdall
family: neighborhoods
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 935cb5d410bf4caacdbba808dfcdb1e4e2a43dc7
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# heimdall: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/heimdall.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/heimdall` at `935cb5d410`](https://github.com/kody-w/heimdall/tree/935cb5d410bf4caacdbba808dfcdb1e4e2a43dc7).

- Evidence: [`kody-w/heimdall` at `935cb5d410`](https://github.com/kody-w/heimdall/tree/935cb5d410bf4caacdbba808dfcdb1e4e2a43dc7) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `c65f2d572f3fc27623af81c1586bf615046f9e47be73108b19231ba034de940d`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/heimdall` at `935cb5d410` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py heimdall --json` from the folder that holds both.
