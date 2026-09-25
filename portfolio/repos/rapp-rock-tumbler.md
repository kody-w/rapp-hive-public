---
repo: kody-w/rapp-rock-tumbler
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: cb3dd662e874b02a1a903fdbab0863d4b876895f
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-rock-tumbler: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-rock-tumbler.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-rock-tumbler` at `cb3dd662e8`](https://github.com/kody-w/rapp-rock-tumbler/tree/cb3dd662e874b02a1a903fdbab0863d4b876895f) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `62a77d5c73981973a70deb8e68e9f8290032a80d86df6aca340bd607c9d550ea`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-rock-tumbler` at `cb3dd662e8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-rock-tumbler --json` from the folder that holds both.
