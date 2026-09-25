---
repo: kody-w/rapp-sentinel-hub
family: agents-rar
line: Agents (RAR)
wave: 2
status: certified
verdict: CLEAN
evidence_commit: b3a4dfbe05ae9bb291b651e552394aa53e3ee84c
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
also_on:
  - estate
links_to:
  - rapp-1
  - rapp-sentinel
---

# rapp-sentinel-hub: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-sentinel-hub.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-sentinel-hub` at `b3a4dfbe05`](https://github.com/kody-w/rapp-sentinel-hub/tree/b3a4dfbe05ae9bb291b651e552394aa53e3ee84c) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f9190c399f457218233ef57c91fe1efae8c700505aecd907d76b0daed5ef3fa3`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Agents (RAR)** line, and also Estate & Ops ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 2 portfolio repo(s): [rapp-1](rapp-1.md) (markdown), [rapp-sentinel](rapp-sentinel.md) (markdown).
Linked from 3: [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md), [rapp-sentinel](rapp-sentinel.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-sentinel-hub` at `b3a4dfbe05` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-sentinel-hub --json` from the folder that holds both.
