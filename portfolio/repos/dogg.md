---
repo: kody-w/dogg
family: dogg-network
wave: 2
status: not yet
verdict: DRIFT
evidence_commit: e9c1a90644981a962b5c8a38fc0c15efdf44bb9d
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# dogg: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/dogg.svg)

**Not yet:** 3 finding(s) from rapp_check: §7.4 chain gap ×3.

- Evidence: [`kody-w/dogg` at `e9c1a90644`](https://github.com/kody-w/dogg/tree/e9c1a90644981a962b5c8a38fc0c15efdf44bb9d) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 3 finding(s), 37 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `196c11f94dc5d57655fb669d0474acff3a690f6996e3884f1fb17d695b4985e0`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Findings (3)

- `tests/fixture_markets_frame.json` · §7.4 chain gap · stream markets:@kody-w/dogg-markets expected seq 0, found 30
- `ticks/864.json` · §7.4 chain gap · stream tick:@kody-w/global expected seq 0, found 864
- `world/576.json` · §7.4 chain gap · stream world:@kody-w/dogg expected seq 0, found 576

## Check it yourself

Clone `kody-w/dogg` at `e9c1a90644` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py dogg --json` from the folder that holds both.
