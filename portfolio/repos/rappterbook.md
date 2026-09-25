---
repo: kody-w/rappterbook
family: rappter
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 4a2af36bd894d2dff5919596d6ef0358234a6cf0
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 4103
header: missing
---

# rappterbook: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbook.svg)

**Not yet:** 12 finding(s) from rapp_check: §9 egg ×10, §12 schema label, verification unavailable; 1 of them unverified.

- Evidence: [`kody-w/rappterbook` at `4a2af36bd8`](https://github.com/kody-w/rappterbook/tree/4a2af36bd894d2dff5919596d6ef0358234a6cf0) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 12 finding(s), 6 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `e2cb0fa4c99f38b4095595de3d07f0d530141dede828eb385a2849e73d28f6f9`.
- "experimental" mentions: 4103 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (12)

- `state/commons/rappid.json` · §12 schema label · schema='?', not 'rapp/1'
- `.` · verification unavailable · bounded frame discovery JSON budget exhausted (unverified)
- `awakening.rappterbook.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `docs/egg/examples/sparky.rappter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `docs/kodyTwinAI.rapp.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/rappterbook-cohesive.network.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `kodyTwinAI.rapp.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `medic.rapp.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `state/phylogeny/founders/azure-mind.rappter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: JSON egg bytes MUST equal canonical(manifest))
- `state/phylogeny/founders/gold-storm.rappter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: JSON egg bytes MUST equal canonical(manifest))
- `state/phylogeny/founders/scarlet-fang.rappter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: JSON egg bytes MUST equal canonical(manifest))
- `state/phylogeny/founders/verdant-vow.rappter.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: JSON egg bytes MUST equal canonical(manifest))

## Check it yourself

Clone `kody-w/rappterbook` at `4a2af36bd8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbook --json` from the folder that holds both.
