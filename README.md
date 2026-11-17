# FreshCart API

A small Flask API starter for the FreshCart project.

[![CI](https://github.com/dm4405770-gif/freshcart-api/actions/workflows/ci.yml/badge.svg)](https://github.com/dm4405770-gif/freshcart-api/actions/workflows/ci.yml)

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements-dev.txt
python app.py
```

The API provides `/` and `/health`.

## Run checks

```bash
flake8 app.py tests
pytest -q
```

Replace `dm4405770-gif/freshcart-api` in the CI badge URL with your GitHub username and repository name.
