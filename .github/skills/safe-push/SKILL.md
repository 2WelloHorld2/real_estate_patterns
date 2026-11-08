---
name: safe-push
description: Review a change for secrets and sensitive data and require approval before Git push.
---

# Safe Push

Before any push: inspect `git status` and staged diff, verify branch/remote, identify untracked files, and review added notebook outputs and dataset files. Search for credentials, tokens, API keys, `.env` files, private records and real tax identifiers (including INN) in data/content; assess false positives rather than blocking innocent variable names. Prevent inclusion of sensitive data until it is removed or explicitly approved for lawful publication. Run available project checks (see `lint-tests`) and summarize their status. Never force-push, publish or overwrite remote history without specific user approval. No permission to execute a push is implied by invoking this skill.
