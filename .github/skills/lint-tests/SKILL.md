---
name: lint-tests
description: Run available linting, tests and relevant analytical checks before a change is published.
---

# Lint Tests

Discover existing Python/test tooling first. Where available, run configured lint checks (prefer `ruff check .` for Python source, excluding generated and irrelevant artifacts), then run `pytest` for existing tests. For notebooks, inspect syntax and relevant pure-code paths without blindly executing cells requiring private data or side effects. Check the project-specific data assumptions in `SPEC.md` if suitable fixtures exist. Capture commands, exit codes, failures and skipped checks. Never claim a check passed unless actually run; do not install dependencies or modify code without permission.
