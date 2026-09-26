---
repo: kody-w/rapp-model-hive
family: hive
line: Hive
wave: 1
status: not yet
verdict: DRIFT
evidence_commit: 113b739e05c4975d0d59e19836d1714b87e9e1ab
checked: 2026-09-26
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 16
header: present
header_pr: https://github.com/kody-w/rapp-model-hive/pull/1
channel: newest
lifecycle: active
also_on:
  - rapp1-core
links_to:
  - rapp-1
  - rapp-workspace
---

# rapp-model-hive: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-model-hive.svg)

**Not yet:** 35 finding(s) from rapp_check: §10 signature verification unavailable ×31, §7.6 duplicate position ×4; 31 of them unverified.

**Version:** none recorded (no root VERSION file and no GitHub release). **Channel:** `newest`: it has no long-term-support pin, so its newest commit is the one in use.

- Evidence: [`kody-w/rapp-model-hive` at `113b739e05`](https://github.com/kody-w/rapp-model-hive/tree/113b739e05c4975d0d59e19836d1714b87e9e1ab) on `main`, checked 2026-09-26.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 35 finding(s), 31 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ca04ebc2e0f233ca9ab0e76d56c67ac2340e36fd718f8b351d1174ae55f303e4`.
- "experimental" mentions: 16 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: present in `README.md`.

## Findings (35)

- `model/hive/streams/avery-laptop.hive.121f71337e33/00000000.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000001.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000002.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000003.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000004.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000005.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000006.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000007.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000008.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.hive.121f71337e33/00000009.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/hive/streams/avery-laptop.manifest.121f71337e33/00000000.json` · §10 signature verification unavailable · detached signature was not checked because no trusted verifier/anchor was supplied (unverified)
- `model/before/streams/avery-laptop.tasks.121f71337e33/00000000.json, model/hive/streams/avery-laptop.tasks.121f71337e33/00000000.json` · §7.6 duplicate position · stream rappid:@contoso/avery-laptop:121f71337e335720c65dc4f7b459c92aea6197460224401810721765fabea47b:tasks has 2 frames at seq 0
- … and 23 more in the raw output

On the map: the **Hive** line, and also RAPP/1 Core ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Links to 2 portfolio repo(s): [rapp-1](rapp-1.md) (markdown), [rapp-workspace](rapp-workspace.md) (markdown).
Linked from 2: [rapp-hive-public](rapp-hive-public.md), [rapp-monorepo](rapp-monorepo.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-model-hive` at `113b739e05` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-model-hive --json` from the folder that holds both.
