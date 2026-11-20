# my-python-app

![CI](https://github.com/TEgor1212/my-python-app/actions/workflows/ci.yml/badge.svg)

Python app with CI — runs pytest on push and PR.

A Python application with a full CI pipeline that lints with flake8 and runs tests with pytest across multiple Python versions (3.10–3.12). Also builds a Docker image on pushes to main.

## Quick Start

```bash
pip install -e .
pytest tests/
```