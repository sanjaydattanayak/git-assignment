# GitHub Actions Pipeline Demo

This repo demonstrates a GitHub Actions workflow that builds and tests a simple Python project.

## Workflow
- Trigger: push or pull request to `main`
- Job: set up Python, install dependencies, run pytest
- Caching: pip cache (optional)

## How to run locally
1. `python -m venv venv`
2. `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
3. `pip install -r requirements.txt`
4. `pytest`