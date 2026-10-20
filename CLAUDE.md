# CLAUDE.md

Guidance for Claude Code when working in this repository.

## What this repository is

Documentation-only repository for the **Tags** project: the project description
(`README.md`), Architecture Decision Records and OpenAPI Specifications. There is no
application code, build or test suite.

## Layout

- `README.md` — project description and repository layout.
- `docs/adr/` — Architecture Decision Records.
  - `README.md` — conventions and the ADR index.
  - `template.md` — starting point for new ADRs.
  - `NNNN-short-title.md` — one decision per file.
- `sec/open-api-specs/` — OpenAPI Specifications, one per API, named `<api-name>.openapi.yaml`.

## Working with ADRs

- Copy `docs/adr/template.md` to the next free number: `NNNN-short-title-in-kebab-case.md`.
  Numbers are sequential and never reused.
- Fill in Status, Date (ISO `YYYY-MM-DD`), Context, Decision, Consequences and Alternatives.
- Add every new ADR to the index table in `docs/adr/README.md`.
- Do not rewrite an accepted ADR. Record a changed decision as a new ADR, and set the old
  one's status to `Superseded by ADR-NNNN`.
- Status values: `Proposed`, `Accepted`, `Rejected`, `Deprecated`, `Superseded by ADR-NNNN`.

## Working with OpenAPI Specifications

- Write specifications in YAML.
- Record significant API design choices as an ADR and reference it from the spec where useful.

## Style

- Markdown, written in English.
- Follow `.editorconfig`: UTF-8, LF line endings, 2-space indentation, final newline.
- Keep links relative so they work on GitHub and locally.
