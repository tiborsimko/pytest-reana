**13 May 2026** This repository is now deprecated.

This repository is end-of-life and is being archived. The fixtures and helpers
previously shipped here have moved to:

- `reana-commons[tests]`, exporting from `reana_commons.testing`
- `reana-db[tests]`, exporting from `reana_db.testing`

The last shim release stays available on PyPI, so existing pinned installs of
`pytest-reana` continue to work; this commit empties the source tree in
preparation for archiving the GitHub project.

New projects should depend on `reana-commons[tests]` and/or `reana-db[tests]`
directly.
