# Contributing

## Branch naming rules

Use one of these prefixes for branches:

- `feature/` for new features
- `bugfix/` for bug fixes
- `hotfix/` for urgent fixes
- `docs/` for documentation changes
- `test/` for test changes
- `chore/` for maintenance tasks

Examples: `feature/add-cart`, `bugfix/health-check`, `docs/update-readme`.

Before opening a pull request, run:

```bash
flake8 app.py tests
pytest -q
```
