# Tools

The two standard-library Python files that made this portfolio, exactly as they ran for the latest version. Each `.py.md` holds one source file in a fenced block, with its SHA-256 above it.

Copy them out and check them (run this in a clone of `kody-w/rapp-hive-public`, inside `portfolio/tools/`):

```bash
python3 - <<'PY'
import hashlib, pathlib, re
fence = chr(96) * 5
for md in sorted(pathlib.Path('.').glob('*.py.md')):
    text = md.read_text(encoding='utf-8')
    source = text.split(fence + 'python\n', 1)[1].rsplit(fence + '\n', 1)[0]
    want = re.search(r'SHA-256 of the source below: .([0-9a-f]+).', text).group(1)
    assert hashlib.sha256(source.encode('utf-8')).hexdigest() == want, md.name
    pathlib.Path(md.name[:-3]).write_text(source, encoding='utf-8')
    print('ok', md.name[:-3], want)
PY
```

Check the published chain (no Hive needed; it clones rapp-1 at the pin):

```bash
python3 -B rapp1_portfolio.py verify ../
```

Crawl again and cut the next version (needs git, a signed-in `gh`, Chrome, and a Hive with `hive_agent.py` from `kody-w/rapp-model-hive`):

```bash
python3 -B rapp1_portfolio.py crawl --hive-agent <path to hive_agent.py> [--denylist <private scanner>]
```
