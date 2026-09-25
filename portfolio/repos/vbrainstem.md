---
repo: kody-w/vbrainstem
family: brainstem
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: ee5499fed56f4d0e46c94f8be034e073adc55b2b
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 2
header: missing
---

# vbrainstem: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/vbrainstem.svg)

**Not yet:** 1 finding(s) from rapp_check: §7.4 chain gap.

- Evidence: [`kody-w/vbrainstem` at `ee5499fed5`](https://github.com/kody-w/vbrainstem/tree/ee5499fed56f4d0e46c94f8be034e073adc55b2b) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `88c39e270098b50bc4dbd2f1731500fa364dd0588037916bed30e9f271a400e8`.
- "experimental" mentions: 2 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `vbrainstem-setup/FRAME.json` · §7.4 chain gap · stream rappid:@kody-w/vbrainstem-setup:228be404333c42b53ecd48fae5e4d9f3a2e10fc459da19065b3f91adce70d228 expected seq 0, found 5

## Check it yourself

Clone `kody-w/vbrainstem` at `ee5499fed5` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py vbrainstem --json` from the folder that holds both.
