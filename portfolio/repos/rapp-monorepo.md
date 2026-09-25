---
repo: kody-w/rapp-monorepo
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 64fa4935eec40aace6e0b73286c30088db72fb57
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 3893
header: missing
---

# rapp-monorepo: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-monorepo.svg)

**Not yet:** 67 finding(s) from rapp_check: §9 egg ×64, verification unavailable ×2, §12 schema label; 2 of them unverified.

- Evidence: [`kody-w/rapp-monorepo` at `64fa4935ee`](https://github.com/kody-w/rapp-monorepo/tree/64fa4935eec40aace6e0b73286c30088db72fb57) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 67 finding(s), 46 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `875cb7912d08dd9982461962bad03a24c39e4e64e534aa4e779f3f31e4e5ef34`.
- "experimental" mentions: 3893 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (67)

- `.` · verification unavailable · bounded discovery incomplete: repository tree limit reached; tail not scanned (unverified)
- `repos/rappter-site/mesh/rappid.json` · §12 schema label · schema='?', not 'rapp/1'
- `.` · verification unavailable · bounded frame discovery JSON budget exhausted (unverified)
- `repos/RAPP/cave/cubbies/kody-w/eggs/cubby-rapp-installer.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP/cave/rapplications/rapp-installer/cubby-rapp-installer.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP/pages/tutorials/commons.egg` · §9 egg · not a conformant rapp/1-egg (schema=rapp/1-egg; §10: invite verification requires estate_owner_rappid)
- `repos/RAPP_Store/api/v1/egg/agent_team.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP_Store/api/v1/egg/bookfactory.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP_Store/api/v1/egg/chainforge.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP_Store/api/v1/egg/cockpit.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP_Store/api/v1/egg/coe_starter_kit.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `repos/RAPP_Store/api/v1/egg/csv_surgeon.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- … and 55 more in the raw output

## Check it yourself

Clone `kody-w/rapp-monorepo` at `64fa4935ee` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-monorepo --json` from the folder that holds both.
