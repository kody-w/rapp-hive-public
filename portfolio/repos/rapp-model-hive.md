---
repo: kody-w/rapp-model-hive
family: hive
wave: 1
status: not yet
verdict: DRIFT
evidence_commit: 83e039f58486afb529b1036087c03e9808a564ca
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 16
header: pr-open
header_pr: https://github.com/kody-w/rapp-model-hive/pull/1
---

# rapp-model-hive: not yet

![RAPP/1: not yet](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-model-hive.svg)

**Not yet:** 35 finding(s) from rapp_check: §10 signature verification unavailable ×31, §7.6 duplicate position ×4; 31 of them unverified.

- Evidence: [`kody-w/rapp-model-hive` at `83e039f584`](https://github.com/kody-w/rapp-model-hive/tree/83e039f58486afb529b1036087c03e9808a564ca) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **DRIFT**, 35 finding(s), 31 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ca04ebc2e0f233ca9ab0e76d56c67ac2340e36fd718f8b351d1174ae55f303e4`.
- "experimental" mentions: 16 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: PR open (https://github.com/kody-w/rapp-model-hive/pull/1).

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

## Check it yourself

Clone `kody-w/rapp-model-hive` at `83e039f584` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-model-hive --json` from the folder that holds both.
