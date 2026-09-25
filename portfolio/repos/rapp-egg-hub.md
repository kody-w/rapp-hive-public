---
repo: kody-w/rapp-egg-hub
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 4c49318fcafe526c56802c50131699006501e3e1
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 11
header: missing
---

# rapp-egg-hub: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-egg-hub.svg)

**Not yet:** 6 finding(s) from rapp_check: §9 egg ×6.

- Evidence: [`kody-w/rapp-egg-hub` at `4c49318fca`](https://github.com/kody-w/rapp-egg-hub/tree/4c49318fcafe526c56802c50131699006501e3e1) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 6 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `31a4529db16f3bc6f8567b7d6873101dc7b365445742ebfdce9d026c9a1fdffa`.
- "experimental" mentions: 11 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (6)

- `eggs/generic-twin.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/grandma-rose.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/kody-w.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/rappterbook-cohesive.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: floats require full-JCS number serialization; use ints/strings)
- `eggs/rock-tumbler.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/wildhaven-ceo.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rapp-egg-hub` at `4c49318fca` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-egg-hub --json` from the folder that holds both.
