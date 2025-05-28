# 0001 - Use Architecture Decision Records (ADRs)

## Status

Accepted

## Context

We need a consistent and lightweight method to document architectural decisions made throughout the lifecycle of this project.

Without proper documentation:
- Decisions are easily forgotten over time.
- Team members may not understand the rationale behind certain technical choices.
- Onboarding new developers becomes more difficult.
- The team may unintentionally revisit the same discussions repeatedly.

A structured and version-controlled approach would help preserve decision history and promote transparency.

## Decision

We will adopt [Architecture Decision Records (ADRs)](https://adr.github.io/) to document significant architectural decisions.

ADRs will:
- Be stored in the `/adr` directory of the repository.
- Use Markdown format.
- Be named with an incrementing number and a short title (e.g., `0002-use-postgres.md`).
- Be created using the [`adr`](https://github.com/npryce/adr-tools) CLI tool or manually, following a standard template.

## Consequences

- All team members are expected to create an ADR when making a key architectural decision.
- Reviews of ADRs will be part of pull requests when relevant.
- Over time, we will build a valuable decision log that serves as project memory.

## Alternatives Considered

- **Wikis**: Less version-controlled and harder to track alongside code.
- **No documentation**: High risk of lost context and duplicated effort.
