---
repo: kody-w/lisppy
family: rapp1-core
line: RAPP/1 Core
wave: 1
status: certified
verdict: CLEAN
evidence_commit: addd6afc1a3362039d06459dcced8ef7406fcbbf
checked: 2026-09-26
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: present
header_pr: https://github.com/kody-w/lisppy/pull/1
channel: newest
lifecycle: active
links_to:
  - rappterbook
---

# lisppy: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/lisppy.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

**Version:** none recorded (no root VERSION file and no GitHub release). **Channel:** `newest`: it has no long-term-support pin, so its newest commit is the one in use.

- Evidence: [`kody-w/lisppy` at `addd6afc1a`](https://github.com/kody-w/lisppy/tree/addd6afc1a3362039d06459dcced8ef7406fcbbf) on `main`, checked 2026-09-26.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `4b8b8bd0ac6781a6356fc3df65bf70ee8d2ba2fd0cb846010516c1844e7b9c44`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: present in `README.md`.

On the map: the **RAPP/1 Core** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 1 portfolio repo(s): [rappterbook](rappterbook.md) (markdown).
Linked from 3: [lisppy-shepherd](lisppy-shepherd.md), [rapp-monorepo](rapp-monorepo.md), [rappterbook](rappterbook.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/lisppy` at `addd6afc1a` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py lisppy --json` from the folder that holds both.
