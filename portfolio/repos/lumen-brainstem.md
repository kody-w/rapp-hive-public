---
repo: kody-w/lumen-brainstem
family: brainstem
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: 11d0aee5659c58d1e3f8dc96f003a8e896ce83ae
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# lumen-brainstem: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/lumen-brainstem.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/lumen-brainstem` at `11d0aee565`](https://github.com/kody-w/lumen-brainstem/tree/11d0aee5659c58d1e3f8dc96f003a8e896ce83ae).

- Evidence: [`kody-w/lumen-brainstem` at `11d0aee565`](https://github.com/kody-w/lumen-brainstem/tree/11d0aee5659c58d1e3f8dc96f003a8e896ce83ae) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `020311302e192dd743bac8bc0d68885714ec506f185f191f962cefcba82782ab`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/lumen-brainstem` at `11d0aee565` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py lumen-brainstem --json` from the folder that holds both.
