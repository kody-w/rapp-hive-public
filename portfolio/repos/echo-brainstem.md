---
repo: kody-w/echo-brainstem
family: brainstem
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: e9f5c4674c440e03b7a89e4bd06d134f377280c1
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# echo-brainstem: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/echo-brainstem.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** for [`kody-w/echo-brainstem` at `e9f5c4674c`](https://github.com/kody-w/echo-brainstem/tree/e9f5c4674c440e03b7a89e4bd06d134f377280c1).

- Evidence: [`kody-w/echo-brainstem` at `e9f5c4674c`](https://github.com/kody-w/echo-brainstem/tree/e9f5c4674c440e03b7a89e4bd06d134f377280c1) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 0 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ec40f1255630a34e50b066839027a6e8757bae3abf9af680b77e54082e6f069a`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/echo-brainstem` at `e9f5c4674c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py echo-brainstem --json` from the folder that holds both.
