# AGENTS.md

## Project context

This is a small Python test project used to evaluate Codex + GitHub workflows.

## Development commands

- Install dependencies: pip install -e . pytest
- Run tests: pytest
- Run linting: python -m compileall src tests

## Coding rules

- Keep changes small and easy to review.
- Add or update tests for every code change.
- Do not modify CI unless explicitly asked.

## Review guidelines

- Flag missing tests as P1.
- Flag risky behavior changes as P1.
- Ignore minor style comments unless they affect readability.
