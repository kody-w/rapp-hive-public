---
repo: kody-w/rapp_orion
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 7ba9bd9d69812c3dc2d418dcd2029c49b379ffe3
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 8
header: missing
---

# rapp_orion: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp_orion.svg)

**Certified:** rapp-1's own checker gave **CLEAN** for [`kody-w/rapp_orion` at `7ba9bd9d69`](https://github.com/kody-w/rapp_orion/tree/7ba9bd9d69812c3dc2d418dcd2029c49b379ffe3).

- Evidence: [`kody-w/rapp_orion` at `7ba9bd9d69`](https://github.com/kody-w/rapp_orion/tree/7ba9bd9d69812c3dc2d418dcd2029c49b379ffe3) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**, 0 finding(s), 0 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `1f2d80410bcae8d0f2a465ba39fc2ad07e5fb1a60e76ec2ee21a44a782688f41`.
- "experimental" mentions: 8 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp_orion` at `7ba9bd9d69` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp_orion --json` from the folder that holds both.
