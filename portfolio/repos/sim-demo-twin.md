---
repo: kody-w/sim-demo-twin
family: twins
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: bf03e7ec77a0da88c12ae62e5fa236340ba2e619
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# sim-demo-twin: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/sim-demo-twin.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/sim-demo-twin` at `bf03e7ec77`](https://github.com/kody-w/sim-demo-twin/tree/bf03e7ec77a0da88c12ae62e5fa236340ba2e619).

- Evidence: [`kody-w/sim-demo-twin` at `bf03e7ec77`](https://github.com/kody-w/sim-demo-twin/tree/bf03e7ec77a0da88c12ae62e5fa236340ba2e619) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `4f90c698977d1e24f3c484561977545a569e394881b84205deba34c04a13b3d2`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/sim-demo-twin` at `bf03e7ec77` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py sim-demo-twin --json` from the folder that holds both.
