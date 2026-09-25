---
repo: kody-w/dogg-planet
family: dogg-network
wave: 2
status: certified
verdict: COMPLIANT
evidence_commit: d9875a45695e499a7aa8004f1a80ce3214ccf765
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# dogg-planet: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/dogg-planet.svg)

**Certified:** rapp-1's own checker gave **COMPLIANT** (every RAPP artifact passes) at the evidence commit.

- Evidence: [`kody-w/dogg-planet` at `d9875a4569`](https://github.com/kody-w/dogg-planet/tree/d9875a45695e499a7aa8004f1a80ce3214ccf765) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **COMPLIANT**, 199 passing artifact(s). The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `ae7aa63f6257262d272f17fbe7b3ce91039fa1f3495decd7cec4ab98636a1cd8`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/dogg-planet` at `d9875a4569` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py dogg-planet --json` from the folder that holds both.
