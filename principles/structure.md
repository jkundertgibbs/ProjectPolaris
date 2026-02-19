# Structure Principles

## Purpose

Specify structural invariants for objects and relationships across the Polaris model.

## Key Concepts

- Canonical flow: `Board -> Project -> Task -> Subtask`.
- Recursive decomposition with traceable lineage.
- Objects should remain agent-readable and inspectable.

## Relationship to Polaris Architecture

Structure principles anchor repository layout and future schema constraints in `specs/task-schema.md`.

## Open Questions

- What minimum object fields are required for cross-manager portability?
