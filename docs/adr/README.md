# Architecture Decision Records

This directory contains the Architecture Decision Records (ADRs) of the Tags project.

## Conventions

- One decision per file, named `ADR-NNNN-short-title-in-kebab-case.md`, with a zero-padded
  four-digit number (e.g. `ADR-0002-tag-identity.md`).
- Numbers are sequential and never reused.
- Start a new record by copying [`template.md`](template.md).
- An accepted ADR is not rewritten; a changed decision gets a new ADR that supersedes the old one,
  and the status of the old one is updated to `Superseded by ADR-NNNN`.

## Status values

`Proposed` · `Accepted` · `Rejected` · `Deprecated` · `Superseded by ADR-NNNN`

## Index

| ADR                                                   | Title                         | Status   |
|-------------------------------------------------------|-------------------------------|----------|
| [ADR-0001](ADR-0001-record-architecture-decisions.md) | Record architecture decisions | Accepted |
