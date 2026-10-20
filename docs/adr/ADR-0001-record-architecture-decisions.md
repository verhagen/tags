# ADR-0001: Record architecture decisions

- **Status:** Accepted
- **Date:** 2026-10-20

## Context

Architectural decisions for the Tags project need to be traceable: what was decided,
why, and which alternatives were considered.

## Decision

We use Architecture Decision Records, as described by Michael Nygard in
[Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions).
ADRs are stored as Markdown files in `docs/adr/`, follow [`template.md`](template.md)
and are listed in the [index](README.md).

## Consequences

- Decisions and their rationale are versioned together with the specifications.
- Each significant decision requires a short write-up and review.
- Superseded decisions remain available for historical context.
