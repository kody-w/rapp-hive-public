---
repo: kody-w/rapp-carts
family: agents-rar
line: Agents (RAR)
wave: 2
status: certified
verdict: CLEAN
evidence_commit: eeed9732be6142cf45a09eb6635a01bd4a508470
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
links_to:
  - cowork-cookbook-rapp
  - racon
  - rapp-egg-hub
  - rapp-mcp
  - rapp-neighborhood-protocol
  - RAPP_Store
---

# rapp-carts: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-carts.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-carts` at `eeed9732be`](https://github.com/kody-w/rapp-carts/tree/eeed9732be6142cf45a09eb6635a01bd4a508470) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `48b42fad649fb7bbd916be42136ec62d46f4232e44821d7676d8040288244229`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Agents (RAR)** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 6 portfolio repo(s): [cowork-cookbook-rapp](cowork-cookbook-rapp.md) (markdown), [racon](racon.md) (markdown), [rapp-egg-hub](rapp-egg-hub.md) (markdown), [rapp-mcp](rapp-mcp.md) (markdown), [rapp-neighborhood-protocol](rapp-neighborhood-protocol.md) (markdown), [RAPP_Store](RAPP_Store.md) (markdown).
Linked from 7: [racon](racon.md), [RAPP](RAPP.md), [RAPP-Bible](RAPP-Bible.md), [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md), [rapp-remix](rapp-remix.md), [rapp-spine](rapp-spine.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-carts` at `eeed9732be` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-carts --json` from the folder that holds both.
