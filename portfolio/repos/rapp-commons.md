---
repo: kody-w/rapp-commons
family: rapp-projects
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: 560eacce518ca3fbf5709b4ceb60e2adc401be84
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-commons: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-commons.svg)

**Not yet:** 1 finding(s) from rapp_check: §9 egg.

- Evidence: [`kody-w/rapp-commons` at `560eacce51`](https://github.com/kody-w/rapp-commons/tree/560eacce518ca3fbf5709b4ceb60e2adc401be84) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 1 finding(s), 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `2b22eb60ed2be12111ee738125a1af7a1177adbc5e697bc2e46d7381e74561c3`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (1)

- `.well-known/neighborhood.egg` · §9 egg · not a conformant rapp/1-egg (schema=rapp/1-egg; §10: invite verification requires estate_owner_rappid)

## Check it yourself

Clone `kody-w/rapp-commons` at `560eacce51` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-commons --json` from the folder that holds both.
