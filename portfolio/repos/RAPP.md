---
repo: kody-w/RAPP
family: rapp1-core
wave: 1
status: not yet
verdict: DRIFT
evidence_commit: 8afc9733e20ccf7e579a58028c29ab9c207087fa
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 144
header: pr-open
header_pr: https://github.com/kody-w/RAPP/pull/120
---

# RAPP: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/RAPP.svg)

**Not yet:** 3 finding(s) from rapp_check: §9 egg ×3.

- Evidence: [`kody-w/RAPP` at `8afc9733e2`](https://github.com/kody-w/RAPP/tree/8afc9733e20ccf7e579a58028c29ab9c207087fa) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 3 finding(s), 6 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `717dfb4c96ffb882c8e44bb4c353a1e952348b678309375257c939ccb6b60ab8`.
- "experimental" mentions: 144 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/RAPP/pull/120).

## Findings (3)

- `cave/cubbies/kody-w/eggs/cubby-rapp-installer.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `cave/rapplications/rapp-installer/cubby-rapp-installer.egg` · §9 egg · not a conformant rapp/1-egg (schema=?; parse: ZIP local and central UTF-8 flags must match exactly)
- `pages/tutorials/commons.egg` · §9 egg · not a conformant rapp/1-egg (schema=rapp/1-egg; §10: invite verification requires estate_owner_rappid)

## Check it yourself

Clone `kody-w/RAPP` at `8afc9733e2` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py RAPP --json` from the folder that holds both.
