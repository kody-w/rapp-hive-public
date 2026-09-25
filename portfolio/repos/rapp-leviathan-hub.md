---
repo: kody-w/rapp-leviathan-hub
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: bfefc798b9b3ce49c4b9c941830607e21aa8e623
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-leviathan-hub: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-leviathan-hub.svg)

**Not yet:** 2 finding(s) from rapp_check: §9 egg ×2.

- Evidence: [`kody-w/rapp-leviathan-hub` at `bfefc798b9`](https://github.com/kody-w/rapp-leviathan-hub/tree/bfefc798b9b3ce49c4b9c941830607e21aa8e623) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 2 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f11e3d00a7bfa59018076bf4f0d8bbf3ed7218a38b45719621a5dd579d028b56`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (2)

- `eggs/kody.leviathan.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `eggs/macrohard.leviathan.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)

## Check it yourself

Clone `kody-w/rapp-leviathan-hub` at `bfefc798b9` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-leviathan-hub --json` from the folder that holds both.
