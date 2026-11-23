# clippa docs

Published docs for [byvfx/clippa](https://github.com/byvfx/clippa). The pages are built from that repo's `main` (`mkdocs build --strict`) and deployed here.

The site is https://byvfx.github.io/clippa-docs/ once GitHub Pages for this repo is set to GitHub Actions.

The case study stays at https://byvfx.github.io/clippa/.

`.github/workflows/docs.yml` runs every 30 minutes and on demand. It skips the build when `byvfx/clippa` main has not changed since the last successful publish.
