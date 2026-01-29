# GitHub Actions + Python Example

A simple project demonstrating GitHub Actions with Python unit tests.

## Project Structure
- `src/` - Source code
- `tests/` - Unit tests
- `.github/workflows/` - GitHub Actions workflows

## Setup env
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install pytest
```

## Running Tests Locally
```bash
python -m pytest tests/
```

## GitHub Actions
The workflow in `.github/workflows/test.yml` automatically runs tests on every push and pull request.
by Xavi
