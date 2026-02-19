# Core Shift

## Problem Definition

File-centric systems optimize for persistence and retrieval but under-specify intent execution and delegation.

## Proposed Polaris Solution

Treat task progression as the primary object model and expose data only when required for execution.

## Structural Outline

- Define the `store -> do` transition.
- Specify task lifecycle stages.
- Clarify data surfacing and release behavior.

## Open Questions

- What minimum metadata is required for safe delegation?
- How should task completion evidence be normalized?
