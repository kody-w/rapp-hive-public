---
repo: kody-w/rappvision-pigeon-post
family: rappvision
wave: 2
status: certified
verdict: CLEAN
evidence_commit: 836983fafa26a905d67e3860187cf3d6b7d9bcfb
checked: 2026-09-25
checker: kody-w/rapp-1 rapp_check.py at 591e014
experimental_mentions: 10
header: missing
---

# rappvision-pigeon-post: certified

![RAPP/1: certified](https://kody-w.github.io/rapp-hive-public/portfolio/badges/rappvision-pigeon-post.svg)

**Certified:** rapp-1's own checker gave **CLEAN** (no RAPP artifacts, found by a complete bounded scan) at the evidence commit.

- Evidence: [`kody-w/rappvision-pigeon-post` at `836983fafa`](https://github.com/kody-w/rappvision-pigeon-post/tree/836983fafa26a905d67e3860187cf3d6b7d9bcfb) on `main`, checked 2026-09-25.
- Checker: [`rapp_check.py` at `591e014`](https://github.com/kody-w/rapp-1/blob/591e014ad39e223b00ab343ae26e5d9a867ebeee/rapp_check.py), verdict **CLEAN**. The raw output stays in the maintainer's sweep folder, outside the Hive; its SHA-256 is `cfcf4ecbf0a480e7abbab00221bd2fbe7966c2f1658ba1593b3c973ff8d1a79b`.
- "experimental" mentions: 10 (whole word, any case, in tracked text files at the evidence commit; tracked, not a gate).
- Network header: not yet added.

## Check it yourself

Clone `kody-w/rappvision-pigeon-post` at `836983fafa` and `kody-w/rapp-1` at `591e014`, then run `python3 -B rapp-1/rapp_check.py rappvision-pigeon-post --json` from the folder that holds both.
