# Contributing

## Purpose

Define how contributors extend Polaris architecture documentation while preserving clarity and structural rigor.

## Prime Contributors

This registry tracks primary long-term contributors and can be expanded as new contributors join.

| Name | Role | Joined | Notes |
| --- | --- | --- | --- |
| John L. Gibbs | Originator | 2026-02-19 | Project originator |

### How To Be Added

To be listed as a Prime Contributor, a contributor should:

1. Make sustained architectural contributions across multiple Polaris domains (for example: principles, governance, attention, specs, or design).
2. Participate in review and refinement of other contributors' proposals.
3. Have their addition approved by the originator or current project maintainers in a pull request.

When adding a new entry, include:

- Name
- Role
- Joined date (`YYYY-MM-DD`)
- One short note describing contribution scope

## Key Concepts

- **Markdown-first collaboration model**: Primary artifacts are markdown documents, not runtime code.
- **Philosophy vs spec separation**: Conceptual assumptions belong in `principles/` and `design/`; interface drafts belong in `specs/`.
- **Issues for execution discussion**: Implementation discussions should be opened as issues, linked to relevant architecture files.
- **Respectful design discourse**: Critique assumptions, cite tradeoffs, and propose alternatives concretely.

## Relationship to Polaris Architecture

Contributions should reinforce the Board -> Project -> Task model and maintain inspectable governance and attention assumptions.

## Open Questions

- What merge criteria should gate philosophy changes vs spec changes?
- Which documents require formal review sign-off?
