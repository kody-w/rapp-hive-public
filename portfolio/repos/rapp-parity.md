---
repo: kody-w/rapp-parity
family: rapp-projects
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: cb5ce3d5224915f18d797280844d53f75f055bd2
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-parity: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-parity.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/rapp-parity` at `cb5ce3d522`](https://github.com/kody-w/rapp-parity/tree/cb5ce3d5224915f18d797280844d53f75f055bd2) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `3c35affda7298e7ada505b35b071861be9152701f489cc463576c7196f38d285`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-parity` at `cb5ce3d522` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-parity --json` from the folder that holds both.
