---
repo: kody-w/rapp-video
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 5516a84177eb3ce156609985cf6cc78ef6f498e2
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 6
header: missing
---

# rapp-video: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-video.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-video` at `5516a84177`](https://github.com/kody-w/rapp-video/tree/5516a84177eb3ce156609985cf6cc78ef6f498e2) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `044bc968fdb03e932f46ced8317fd6fecb93fe3c5692032fb54f6704581f4069`.
- "experimental" mentions: 6 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-video` at `5516a84177` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-video --json` from the folder that holds both.
