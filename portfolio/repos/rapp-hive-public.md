---
repo: kody-w/rapp-hive-public
family: hive
wave: 1
status: certified
verdict: CLEAN
evidence_commit: 849c775fa1ea5af50c39c3398d821c1d2cab8bda
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 372
header: present
---

# rapp-hive-public: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-hive-public.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rapp-hive-public` at `849c775fa1`](https://github.com/kody-w/rapp-hive-public/tree/849c775fa1ea5af50c39c3398d821c1d2cab8bda) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `a57abfdd32e977223ed69718ed69672e1a9be7f5ef32e8966979453885e80253`.
- "experimental" mentions: 372 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: present in `README.md`.

## Check it yourself

Clone `kody-w/rapp-hive-public` at `849c775fa1` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-hive-public --json` from the folder that holds both.
