---
repo: kody-w/pkstop-pike-place-market
family: neighborhoods
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: d2962af69eed6ddcd44ada3bdc7c6e74d62c997f
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 1
header: missing
---

# pkstop-pike-place-market: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/pkstop-pike-place-market.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/pkstop-pike-place-market` at `d2962af69e`](https://github.com/kody-w/pkstop-pike-place-market/tree/d2962af69eed6ddcd44ada3bdc7c6e74d62c997f) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 1 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `bc16843e0f7495d995a01595c95f6c7463561a8c88ef5d64a4b715315675b378`.
- "experimental" mentions: 1 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/pkstop-pike-place-market` at `d2962af69e` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py pkstop-pike-place-market --json` from the folder that holds both.
