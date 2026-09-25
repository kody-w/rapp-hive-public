---
repo: kody-w/rapp-release-train
family: release
line: Release Channels
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 5575c6eb6ceab0c369c125c320de2660a80809b5
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 6
header: missing
links_to:
  - rapp-canary
  - rapp-map
  - rapp-static-apis
---

# rapp-release-train: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-release-train.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-release-train` at `5575c6eb6c`](https://github.com/kody-w/rapp-release-train/tree/5575c6eb6ceab0c369c125c320de2660a80809b5) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `80398384c27f2b406b319a83f7aa247eb3750cd19a65757684b1b0bcc23487e9`.
- "experimental" mentions: 6 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Release Channels** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 3 portfolio repo(s): [rapp-canary](rapp-canary.md) (markdown), [rapp-map](rapp-map.md) (markdown), [rapp-static-apis](rapp-static-apis.md) (markdown).
Linked from 2: [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-release-train` at `5575c6eb6c` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-release-train --json` from the folder that holds both.
