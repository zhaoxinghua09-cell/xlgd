# Changelog

All notable changes to **XLGD** (the umbrella mark) are recorded here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

Nothing in this repository is a ratified standard. Names are project identifiers
only — no entity and no trademark has been registered.

## [Unreleased]

### Added

- **Machine-readable entry point** — `ecosystem.json` (the umbrella index:
  layers, repositories, roles, licence, status) and `llms.txt`, so that AI
  agents and crawlers can resolve the XLGD / LGD / UIBC structure without
  scraping prose.
- **`CHANGELOG.md`** — this file. The umbrella previously had no release
  history, so a reader could not tell what changed or when.
- **`SECURITY.md`** — a security contact and disclosure route.
- **`CITATION.cff`** — machine-readable citation metadata, so the umbrella can
  be cited like the layers it fronts.
- **Machine-readable entry section** appended to `README.md`, linking the index
  files above.

### Notes

- No release has been cut yet; the umbrella is fronted by the released layers
  (`lgd-theory`, `uibc-core`, `silent-failure-catalog`) which carry their own
  versioned changelogs and tags.
