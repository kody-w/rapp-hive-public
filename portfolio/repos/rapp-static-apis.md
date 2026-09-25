---
repo: kody-w/rapp-static-apis
family: tools
line: Tools & Apps
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 6d0d094696187816f80cb7449528ac5cec373fdb
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
links_to:
  - rapp-map
  - rapp-mcp
  - RAR
---

# rapp-static-apis: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-static-apis.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-static-apis` at `6d0d094696`](https://github.com/kody-w/rapp-static-apis/tree/6d0d094696187816f80cb7449528ac5cec373fdb) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `e3341ad052e00b3a9430279ea34b591ba0806d66be28a3982e88530eba6fbba5`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Tools & Apps** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 3 portfolio repo(s): [rapp-map](rapp-map.md) (markdown), [rapp-mcp](rapp-mcp.md) (markdown), [RAR](RAR.md) (markdown).
Linked from 16: [rapp-ai](rapp-ai.md), [rapp-basket](rapp-basket.md), [RAPP-Bible](RAPP-Bible.md), [rapp-commons](rapp-commons.md), [rapp-dataverse](rapp-dataverse.md), [rapp-hive-public](rapp-hive-public.md), [rapp-lantern](rapp-lantern.md), [rapp-mcp](rapp-mcp.md), [rapp-monorepo](rapp-monorepo.md), [rapp-release-train](rapp-release-train.md), [rapp-snap](rapp-snap.md), [rapp-spine](rapp-spine.md), [rapp-static-brainstem](rapp-static-brainstem.md), [rapp-static-mcp](rapp-static-mcp.md), [rappter-prompts](rappter-prompts.md), [rappter-vui](rappter-vui.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-static-apis` at `6d0d094696` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-static-apis --json` from the folder that holds both.
