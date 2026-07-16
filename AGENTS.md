# Project: lazyboards-demo

No tech stack established yet — this is currently an empty demo repository for lazyboards.
GitHub for tracking and pull requests.

## Critical Rules

- Read the relevant `docs/` file before working in its topic area.
- Test first; assert behavior rather than implementation details.
- Never commit secrets, credentials, API keys, or PII.
- Never expose PII or stack traces in user-facing errors.
- Keep tickets well scoped: one ticket equals one pull request.
- Use feature worktrees; never implement directly in the main worktree.

## Reference Docs

- `docs/git-workflow.md` — branching, commits, pull requests, and versioning.
- Additional topic guidance lives in `docs/<topic>.md` and is read on demand.

## Sandbox Image

- `.cenci/Dockerfile` is the reviewed, repository-specific sandbox image. Rebuild it
  with `cenci sandbox build` after stack or Dockerfile changes.
