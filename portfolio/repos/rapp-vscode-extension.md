---
repo: kody-w/rapp-vscode-extension
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 774e9f428603b2a828432c3f1ca8f8bba26d89ed
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: no-readme
---

# rapp-vscode-extension: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-vscode-extension.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-vscode-extension` at `774e9f4286`](https://github.com/kody-w/rapp-vscode-extension/tree/774e9f428603b2a828432c3f1ca8f8bba26d89ed) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ca78a39543256be480c7f1f0629e8fcb694d738616b984bc5ea6a84b85426476`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: no README (skipped).

## Check it yourself

Clone `kody-w/rapp-vscode-extension` at `774e9f4286` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-vscode-extension --json` from the folder that holds both.
