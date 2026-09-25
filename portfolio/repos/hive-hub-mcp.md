---
repo: kody-w/hive-hub-mcp
family: hive
line: Hive
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 4a3424b2f4891d52a56b12d8d5028d967435c912
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: pr-open
header_pr: https://github.com/kody-w/hive-hub-mcp/pull/1
links_to:
  - hive-hub-join
  - rapp-hive-hub-join
---

# hive-hub-mcp: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/hive-hub-mcp.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/hive-hub-mcp` at `4a3424b2f4`](https://github.com/kody-w/hive-hub-mcp/tree/4a3424b2f4891d52a56b12d8d5028d967435c912) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `585097cf904567020078e303f4317f652f4cbad7787e124dfcd18cb1c6f5a993`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/hive-hub-mcp/pull/1).

On the map: the **Hive** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 2 portfolio repo(s): [hive-hub-join](hive-hub-join.md) (markdown), [rapp-hive-hub-join](rapp-hive-hub-join.md) (markdown).
Linked from 4: [hive-hub-join](hive-hub-join.md), [rapp-hive-hub-join](rapp-hive-hub-join.md), [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/hive-hub-mcp` at `4a3424b2f4` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py hive-hub-mcp --json` from the folder that holds both.
