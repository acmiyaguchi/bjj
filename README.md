# bjj notes

## quickstart

```bash
uv sync
source .venv/bin/activate
mkdocs serve
```

Dependencies need to be updated for netlify builds.

```bash
uv pip compile pyproject.toml > requirements.txt
```
