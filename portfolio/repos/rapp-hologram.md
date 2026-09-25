---
repo: kody-w/rapp-hologram
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 4c981887623b341fa094d4ba70126c4631a2c581
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-hologram: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-hologram.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-hologram` at `4c98188762`](https://github.com/kody-w/rapp-hologram/tree/4c981887623b341fa094d4ba70126c4631a2c581) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ac162b6666e5f1abc2d3f38a131dabdb306dc620c64c5688defb24cf5b3c81fa`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-hologram` at `4c98188762` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-hologram --json` from the folder that holds both.
