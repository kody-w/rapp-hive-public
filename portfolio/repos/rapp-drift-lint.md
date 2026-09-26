---
repo: kody-w/rapp-drift-lint
family: rapp1-core
line: RAPP/1 Core
wave: 1
status: certified
verdict: CLEAN
evidence_commit: fccad3378df2ef3f16805e92b8bf35f3d40347a3
checked: 2026-09-26
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 0
header: present
header_pr: https://github.com/kody-w/rapp-drift-lint/pull/2
channel: newest
lifecycle: active
---

# rapp-drift-lint: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rapp-drift-lint.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

**Version:** none recorded (no root VERSION file and no GitHub release). **Channel:** `newest`: RAPP/1 names no long-term-support pin for it, so its newest commit is the one in use.

- Evidence: [`kody-w/rapp-drift-lint` at `fccad3378d`](https://github.com/kody-w/rapp-drift-lint/tree/fccad3378df2ef3f16805e92b8bf35f3d40347a3) on `main`, checked 2026-09-26.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `bd2fbdb226333db8a5a33dcb8339cb4d54c6a1050949ec15674a367effcff571`.
- "experimental" mentions: 0 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: present in `README.md`.

On the map: the **RAPP/1 Core** line ([subway map](https://kody-w.github.io/rapp-hive-public/portfolio/subway.html)).

## Links

Linked from 3: [RAPP](RAPP.md), [rapp-egg-hub](rapp-egg-hub.md), [rapp-hive-public](rapp-hive-public.md).

Counted from markdown links to `github.com/kody-w/<repo>` or `kody-w.github.io/<repo>`, pin files, workflow `uses:` and `repository:` lines, and submodules, at the evidence commit; only public repos in this portfolio count.

## Check it yourself

Clone `kody-w/rapp-drift-lint` at `fccad3378d` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rapp-drift-lint --json` from the folder that holds both.
