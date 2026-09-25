---
repo: kody-w/rappter-vui
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 20d949bbd78cc6a994dfb28c6da818347e1f3072
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rappter-vui: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappter-vui.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappter-vui` at `20d949bbd7`](https://github.com/kody-w/rappter-vui/tree/20d949bbd78cc6a994dfb28c6da818347e1f3072) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `1a14c7a9d3bb024118eee4995654f82e5a85630649f9c49daba5433297dd0a11`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappter-vui` at `20d949bbd7` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappter-vui --json` from the folder that holds both.
