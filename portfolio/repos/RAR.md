---
repo: kody-w/RAR
family: rar-registry
wave: 1
status: not yet
verdict: DRIFT
evidence_commit: ecf5f52312cf083eaedf5e0aa8782debc7f0af4b
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 161
header: pr-open
header_pr: https://github.com/kody-w/RAR/pull/1115
---

# RAR: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAR.svg)

**Not yet:** 3 finding(s) from rapp_check: §9 egg ×2, verification unavailable; 1 of them unverified.

- Evidence: [`kody-w/RAR` at `ecf5f52312`](https://github.com/kody-w/RAR/tree/ecf5f52312cf083eaedf5e0aa8782debc7f0af4b) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 3 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a9b0d3583b30c89a05aafc7f3f2a84a479193db4548e407d046c8662544ebc04`.
- "experimental" mentions: 161 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/RAR/pull/1115).

## Findings (3)

- `.` · verification unavailable · bounded frame discovery JSON budget exhausted (unverified)
- `stacks/microsoft-365-team/microsoft-365-team.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `stacks/neighborhood-starter/neighborhood-starter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/RAR` at `ecf5f52312` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAR --json` from the folder that holds both.
