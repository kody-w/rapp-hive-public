---
repo: kody-w/rapp-roadside
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 8082439a103572faf2d46fde204baa8eb4bb76de
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-roadside: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-roadside.svg)

**Not yet:** 1 finding(s) from rapp_check: §7.6 duplicate position.

- Evidence: [`kody-w/rapp-roadside` at `8082439a10`](https://github.com/kody-w/rapp-roadside/tree/8082439a103572faf2d46fde204baa8eb4bb76de) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `5b1932680a92ba249df95e59fea1177592792df542d0257fb6a7e0804c6ab393`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `rev-13-frame.json, roadside-frame.json` · §7.6 duplicate position · stream rappid:@kody-w/rar-installer-troubleshooter:296872e9cd739d0549707b5c22abfd3654c3667652ea55dedaa5621b9e5f733b has 2 frames at seq 0

## Check it yourself

Clone `kody-w/rapp-roadside` at `8082439a10` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-roadside --json` from the folder that holds both.
