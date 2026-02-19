# Attention Model

## Problem Definition

Input events are treated as discrete commands rather than signals within a continuous attention context.

## Proposed Polaris Solution

Treat attention as the control substrate: infer intent, prepare actions, and require confirm/redirect paths.

## Structural Outline

- Attention signal taxonomy.
- Inference-to-action pipeline.
- Inspectability and override surfaces.

## Open Questions

- Which inferred actions can be pre-staged without confirmation?
- How should uncertainty be represented to users?
