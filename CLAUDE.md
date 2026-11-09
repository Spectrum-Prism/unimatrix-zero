# Working in unimatrix-zero

Read `README.md` for the repo layout and conventions.

## Branching

- The default branch is `Prism`.
- Anything that will run or be deployed (code, scripts, configs) goes on a feature
  branch and reaches `Prism` through a pull request for Rob to review. Never push it
  straight to `Prism`.
- Low-stakes changes (anything under `notes/`, typo fixes, documentation-only edits)
  may be pushed directly to `Prism`.
- When unsure which category a change falls in, use a pull request.

## Other rules

- Never commit secrets. `.env` files are gitignored for that reason.
- Every new project in `projects/` gets its own `README.md`.
