# 102V-flask — agent notes

## Stack
- **Python 3.14**, **Flask >=3.1.3**, **uv** (not pip/poetry/virtualenv) package manager
- Single app entrypoint: `main.py` (Flask app `app`)
- Single template: `templates/index.html`

## Commands
```bash
uv run flask --app main run --debug
```

## Notable
- Windows-only dev environment; `.venv` is local (gitignored)
- No tests, no linter, no type checker configured
- No CI/CD config present
- README is sparse — do not rely on it for details
