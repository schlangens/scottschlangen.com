# AGENTS.md

## Cursor Cloud specific instructions

This repo is a single **Hugo** static site (`scottschlangen.com`) — no backend, DB, or API. Standard build/run commands live in `README.md`.

### Services

| Task | Command | Notes |
|------|---------|-------|
| Dev server | `hugo server -D` | Serves at `http://localhost:1313` (drafts enabled). This is the only "service". |
| Production build | `hugo --minify --gc` | Outputs to `./public` (gitignored). Mirrors CI in `.github/workflows/publish.yml`. |
| Lint / tests | (none) | There is no lint or automated test suite. "Testing" means building and viewing the site. |

### Non-obvious caveats

- **Hugo must be the Extended edition** (the config's `customSCSS` requires the SCSS/SASS compiler). CI pins `HUGO_VERSION: 0.117.0`; the VM snapshot has `hugo_extended` 0.117.0 installed. Verify with `hugo version` (must contain `+extended`).
- **The theme is a git submodule** at `themes/hugo-coder-forked` (see `.gitmodules`). The site will not build if it is missing — the startup update script runs `git submodule update --init --recursive` to keep it populated.
- If `hugo` complains about a lock, delete the stray `.hugo_build.lock` file at the repo root and rerun.
