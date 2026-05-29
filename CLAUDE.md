# DomesticTuning-Wiki — Claude Code Instructions

## Auto-versioning rule
Every commit that modifies `index.html` MUST increment the patch version.
- Find the current version in the `APP_VERSION` constant near the top of `index.html`
- Increment the patch number (e.g. `1.0.3` → `1.0.4`)
- Update the version constant before committing
- Include the new version number in the commit message, e.g. `feat: add search highlight [v1.0.4]`

## Stack
- Single file app: `index.html`
- Hosted: GitHub Pages (zwhill.github.io/DomesticTuning-Wiki)
- CORS proxy: cshelper-proxy.zwhill.workers.dev
- Anthropic API: claude-sonnet-4-20250514

## Repo
github.com/zwhill/DomesticTuning-Wiki
