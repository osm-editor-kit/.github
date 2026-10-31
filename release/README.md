# Shared release files

The package repositories of this organisation use the same release setup. These files are the originals. Copy them when they change:

| File here | Copy in every repository |
| --- | --- |
| `release.ts` | `scripts/release.ts` |
| `changeset-README.md` | `.changeset/README.md` |
| `pre-push` | `.husky/pre-push` |
| `AGENTS-section.md` | section in `AGENTS.md` |
| `README-release-section.md` | section `## Release` in `README.md` |

`maplibre-editor-layer-index` keeps its own automatic `release.yml` for the weekly data updates.
