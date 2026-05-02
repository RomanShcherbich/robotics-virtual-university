# AGENTS.md

## Cursor Cloud specific instructions

This repository (`robotics-virtual-university`) is a newly initialized Python-oriented project. The `.gitignore` covers Python bytecode, virtual environments, Django/Flask, Celery, Redis, Jupyter, Streamlit, and Marimo patterns.

### Current state

- **No application code, dependencies, or build configuration exists yet.** The repo contains only `.gitignore` and `LICENSE` (Apache 2.0).
- Python 3.12 is available in the base environment.
- There are no lint, test, or build commands to run until source code is added.

### For future agents

- When source code is added, check for `pyproject.toml`, `requirements.txt`, or similar dependency manifests and install accordingly.
- The `.gitignore` hints at possible use of Django, Flask, Celery, Redis, RabbitMQ, Jupyter, Streamlit, or Marimo — watch for these as the project evolves.
- No services, ports, or startup commands are defined yet.
