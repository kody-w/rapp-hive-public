---
repo: kody-w/rappterbook-agent-dna
family: rappter
wave: 2
status: certified
verdict: CLEAN
evidence_commit: b054f180c8f20a3b3224b803957994671ef3a8b8
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rappterbook-agent-dna: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappterbook-agent-dna.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappterbook-agent-dna` at `b054f180c8`](https://github.com/kody-w/rappterbook-agent-dna/tree/b054f180c8f20a3b3224b803957994671ef3a8b8) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `743f11031ac1713395b2c5f96523b5d3f23162d2d118c07aeb0eb0191b70a2fb`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappterbook-agent-dna` at `b054f180c8` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappterbook-agent-dna --json` from the folder that holds both.
