---
repo: kody-w/rapp-agents
family: neighborhoods
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 3de844fc39195b8a73246f4f0598cb768b57ca05
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-agents: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-agents.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-agents` at `3de844fc39`](https://github.com/kody-w/rapp-agents/tree/3de844fc39195b8a73246f4f0598cb768b57ca05) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `aef11f560d603c90dc5abf14e3f85631bc0f43a19816c6926a1be243bf72a411`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-agents` at `3de844fc39` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-agents --json` from the folder that holds both.
