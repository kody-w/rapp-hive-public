---
repo: kody-w/rapp-bench
family: rapp-projects
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 1b157a8b5449d401177f9862706fccad9d338330
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: missing
---

# rapp-bench: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-bench.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-bench` at `1b157a8b54`](https://github.com/kody-w/rapp-bench/tree/1b157a8b5449d401177f9862706fccad9d338330) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a41ea2a3664fdb5c84e54b226e96959dae1346eceafc2ec79ab9a5b299093d24`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rapp-bench` at `1b157a8b54` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-bench --json` from the folder that holds both.
