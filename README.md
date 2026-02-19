# Project Polaris

Project Polaris is an open-source architectural research initiative for a task-centric operating system model designed for human and AI agents.

Originated by **John L. Gibbs**.

## Core Shift: Store -> Do

Traditional systems optimize for storing and retrieving files. Polaris prioritizes declaring intent, decomposing work, and coordinating execution.

- Legacy orientation: `"store this"`
- Polaris orientation: `"do this"`

See [Core Shift Project](projects/core-shift/README.md) and [Why Now](projects/why-now/README.md).

## What MUX Means

MUX (Multi-Environment User Experience) is a device-agnostic interaction model that spans desktop, mobile, wearable, voice, and future interfaces.

- Interaction is bound to identity, not hardware.
- Work is represented as projects, tasks, and subtasks.
- Attention signals drive preparation and confirmation loops.

See [Board Model](projects/board-model/README.md) and [Attention Model](projects/attention-model/README.md).

## High-Level Architecture

- **Board**: Activity surface for mission-oriented work.
- **Project**: Declared mission with bounded scope.
- **Task/Subtask**: Recursive decomposition unit.
- **Manager**: Persistent orchestration layer across time and devices.
- **Roles**: Human or AI governance actors with explicit authority.

Flow:

`Board -> Project -> Task -> Subtask -> ...`

See [Manager Architecture](projects/manager-architecture/README.md), [Governance Model](projects/governance-model/README.md), and [Global Coordination](projects/global-coordination/README.md).

## Active

- [Define Manager identity continuity baseline](projects/manager-architecture/README.md)
- [Draft attention inference and override contract](projects/attention-model/README.md)

## In Review

- [Board object boundaries and project lifecycle](projects/board-model/README.md)
- [Role model and escalation semantics](projects/governance-model/README.md)

## Backlog

- [Global manager-to-manager task negotiation](projects/global-coordination/README.md)
- [Rationale and ecosystem timing analysis](projects/why-now/README.md)

## Completed

- [Initial articulation of the store-to-do transition](projects/core-shift/README.md)

## Repository Structure

- **Philosophy layer**: `principles/`, `design/`, `board/`
  - Core assumptions, structural invariants, and UX language.
- **Governance layer**: `governance/`, `manager/`, `global/`
  - Roles, authority, escalation, and inter-manager coordination.
- **Attention layer**: `attention/`
  - Inference, overrides, inspectability, and privacy boundaries.
- **Spec layer**: `specs/`
  - Draft interface and schema definitions.
- **Runtime layer**: `runtime/`
  - Placeholder containers for future implementation.
- **Open questions layer**: `open-questions/`
  - Explicit unresolved design decisions.
