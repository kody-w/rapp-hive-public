---
repo: kody-w/RAPP_Store
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: c979a60e21b74d17b0ec1421821220721acd39e8
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 76
header: missing
---

# RAPP_Store: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP_Store.svg)

**Not yet:** 26 finding(s) from rapp_check: §9 egg ×26.

- Evidence: [`kody-w/RAPP_Store` at `c979a60e21`](https://github.com/kody-w/RAPP_Store/tree/c979a60e21b74d17b0ec1421821220721acd39e8) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 26 finding(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `0de37196bfaec192374ae2f7db8b2a42db568457e406f0a78dff668d3775ecc7`.
- "experimental" mentions: 76 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (26)

- `api/v1/egg/agent_team.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/bookfactory.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/chainforge.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/cockpit.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/coe_starter_kit.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/csv_surgeon.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/dock_scotty-1.0.0-0df25928ffade880d912bb76907ad78f85506ed1c170f6f9056a6fe770601972.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/egg_hatcher.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/json_doctor.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/log_detective.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/markdown_medic.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `api/v1/egg/novell.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- … and 14 more in the raw output

## Check it yourself

Clone `kody-w/RAPP_Store` at `c979a60e21` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP_Store --json` from the folder that holds both.
