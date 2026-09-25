---
repo: kody-w/rapp-crispy
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 5fb6086f044d67b5b4d3163f666daa9fdc563f98
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-crispy: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-crispy.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/rapp-crispy` at `5fb6086f04`](https://github.com/kody-w/rapp-crispy/tree/5fb6086f044d67b5b4d3163f666daa9fdc563f98) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `735a69b36575f12900581f34fbf5f3d1a074bb8897622d7e35c22420373577cc`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `rapp_crispy/eggs/rapp_crispy.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rapp-crispy` at `5fb6086f04` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-crispy --json` from the folder that holds both.
