---
repo: kody-w/copilot-harness-sdk
family: rapp-related
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 8683889de22b9239f97c27e9f3e219d22762c4dd
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 40
header: missing
---

# copilot-harness-sdk: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/copilot-harness-sdk.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/copilot-harness-sdk` at `8683889de2`](https://github.com/kody-w/copilot-harness-sdk/tree/8683889de22b9239f97c27e9f3e219d22762c4dd) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `f195f3b6a0bd3097c1e222eba8e26af928fd44060ce9caeb5ce61c01ad9ca97e`.
- "experimental" mentions: 40 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/copilot-harness-sdk` at `8683889de2` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py copilot-harness-sdk --json` from the folder that holds both.
