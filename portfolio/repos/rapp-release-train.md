---
repo: kody-w/rapp-release-train
family: release-channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 5575c6eb6ceab0c369c125c320de2660a80809b5
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 6
header: missing
---

# rapp-release-train: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-release-train.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp-release-train` at `5575c6eb6c`](https://github.com/kody-w/rapp-release-train/tree/5575c6eb6ceab0c369c125c320de2660a80809b5).

- Evidence: [`kody-w/rapp-release-train` at `5575c6eb6c`](https://github.com/kody-w/rapp-release-train/tree/5575c6eb6ceab0c369c125c320de2660a80809b5) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `80398384c27f2b406b319a83f7aa247eb3750cd19a65757684b1b0bcc23487e9`.
- "experimental" mentions: 6 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-release-train` at `5575c6eb6c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-release-train --json` from the folder that holds both.
