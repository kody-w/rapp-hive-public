---
repo: kody-w/rapp-test-neighbor
family: neighborhoods
line: Neighborhoods
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: d830223edf2c19c84e3185195daa71acf693a9de
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
links_to:
  - RAPP
  - rapp-1
  - rapp-neighborhood-protocol
  - rapp-vneighborhood
  - RAPPcards
---

# rapp-test-neighbor: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-test-neighbor.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/rapp-test-neighbor` at `d830223edf`](https://github.com/kody-w/rapp-test-neighbor/tree/d830223edf2c19c84e3185195daa71acf693a9de) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `e17135014c15ee864d9bb7a0832e2ba4656a7ab80cb7b3fe299937749f1c5bed`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Neighborhoods** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 5 portfolio repo(s): [RAPP](RAPP.md) (markdown), [rapp-1](rapp-1.md) (markdown), [rapp-neighborhood-protocol](rapp-neighborhood-protocol.md) (markdown), [rapp-vneighborhood](rapp-vneighborhood.md) (markdown), [RAPPcards](RAPPcards.md) (markdown).
Linked from 3: [RAPP](RAPP.md), [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-test-neighbor` at `d830223edf` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-test-neighbor --json` from the folder that holds both.
