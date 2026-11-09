# unimatrix-zero

A shared virtual realm for all.

A general-purpose workbench: scripts, configs, notes, and experiments built by
Spectrum-Prism with Claude. Anything goes; each folder below holds one kind of thing.

## Layout

| Folder      | What goes in it                                              |
|-------------|--------------------------------------------------------------|
| `projects/` | Self-contained projects, one subfolder each                  |
| `scripts/`  | Standalone utility scripts (shell, Python, etc.)             |
| `configs/`  | Config files and dotfiles worth keeping under version control |
| `notes/`    | Markdown notes, write-ups, and reference material            |

## Conventions

- Default branch is `Prism`.
- Never commit secrets (API keys, passwords, tokens). Use `.env` files, which are ignored by `.gitignore`.
- Each project in `projects/` gets its own `README.md` explaining what it is and how to run it.
- Code, scripts, and configs reach `Prism` through a pull request from a feature branch,
  reviewed before merging. Low-stakes changes (notes, typo fixes, docs) can be pushed
  straight to `Prism`.

## License

[MIT](LICENSE)
