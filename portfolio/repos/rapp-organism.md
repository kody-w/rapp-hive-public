---
repo: kody-w/rapp-organism
family: organism
line: Organism & Platform
wave: 2
status: certified
verdict: CLEAN
evidence_commit: fa6e8c9f63177c185943514d69d158c62ad1a873
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 206
header: missing
links_to:
  - dogg
  - rapp-1
---

# rapp-organism: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-organism.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-organism` at `fa6e8c9f63`](https://github.com/kody-w/rapp-organism/tree/fa6e8c9f63177c185943514d69d158c62ad1a873) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `808c33043a820a910d8c597e2ab6cc1666b730d4ac4fd9613584a10554485f24`.
- "experimental" mentions: 206 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

On the map: the **Organism & Platform** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 2 portfolio repo(s): [dogg](dogg.md) (markdown), [rapp-1](rapp-1.md) (markdown).
Linked from 3: [dogg](dogg.md), [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-organism` at `fa6e8c9f63` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-organism --json` from the folder that holds both.
