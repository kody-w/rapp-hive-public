---
repo: kody-w/dynamics365-business-process-api
family: rapp-related
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 0c04dc2ce247ddf4d94f0cb5c8d4d5e088e9f977
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# dynamics365-business-process-api: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/dynamics365-business-process-api.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/dynamics365-business-process-api` at `0c04dc2ce2`](https://github.com/kody-w/dynamics365-business-process-api/tree/0c04dc2ce247ddf4d94f0cb5c8d4d5e088e9f977) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `6c2087d4389a0576fa02024ac938ce91f4d5cf57c9019db789f68225a089accd`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/dynamics365-business-process-api` at `0c04dc2ce2` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py dynamics365-business-process-api --json` from the folder that holds both.
