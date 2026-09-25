---
repo: kody-w/tide-brainstem
family: brainstem
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 72162a8c6b97c344caff2c102bd897e725d180ef
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# tide-brainstem: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/tide-brainstem.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/tide-brainstem` at `72162a8c6b`](https://github.com/kody-w/tide-brainstem/tree/72162a8c6b97c344caff2c102bd897e725d180ef).

- Evidence: [`kody-w/tide-brainstem` at `72162a8c6b`](https://github.com/kody-w/tide-brainstem/tree/72162a8c6b97c344caff2c102bd897e725d180ef) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `56de4a21a12abe16ef00e0551de5bd9b1f536fc7d1a674e4b3d6fa38a6c36ab9`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/tide-brainstem` at `72162a8c6b` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py tide-brainstem --json` from the folder that holds both.
