# Project Polaris

Project Polaris explores what an operating system would look like if it managed attention and coordinated intelligence instead of storing files.

Project Polaris is an open-source architectural research initiative exploring a task-centric operating system paradigm for human and AI agents.

Polaris reframes computing from file management to coordinated execution.

Originated by John L. Gibbs.
Origination date: 19 February, 2026.

---

## Core Shift: Store -> Do

Traditional systems optimize for storing and retrieving files.
Polaris optimizes for declaring intent, decomposing work, and coordinating execution.

* Legacy orientation: `"store this"`
* Polaris orientation: `"do this"`

See:

* [Core Shift](projects/core-shift/README.md)
* [Why Now](projects/why-now/README.md)

---

## What MUX Means

MUX (Multi-Environment User Experience) is a device-agnostic interaction paradigm that spans desktop, mobile, wearable, voice, and future modalities.

* Interaction is bound to identity, not hardware.
* Work is represented as projects, tasks, and subtasks.
* Attention signals drive preparation and confirmation loops.

See:

* [Board Model](projects/board-model/README.md)
* [Attention Model](projects/attention-model/README.md)

---

## High-Level Architecture

Board: Activity surface for mission-oriented work.
Project: Declared mission with bounded scope.
Task: Executable unit of intent.
Subtask: Recursive decomposition of work.
Manager: Persistent orchestration layer across time and devices.
Roles: Human or AI governance actors with explicit authority.

Flow:

```
Board -> Project -> Task -> Subtask -> ...
```

See:

* [Manager Architecture](projects/manager-architecture/README.md)
* [Governance Model](projects/governance-model/README.md)
* [Global Coordination](projects/global-coordination/README.md)

---

## Current Board State

### Active

* Define Manager identity continuity baseline
* Draft attention inference and override contract

### In Review

* Board object boundaries and project lifecycle
* Role model and escalation semantics

### Backlog

* Global manager-to-manager task negotiation
* Rationale and ecosystem timing analysis

### Completed

* Initial articulation of the store-to-do transition

---

## Repository Structure

### Philosophy Layer

`principles/`, `design/`, `board/`
Core assumptions, structural invariants, UX language.

### Governance Layer

`governance/`, `manager/`, `global/`
Authority models, escalation paths, inter-manager coordination.

### Attention Layer

`attention/`
Inference models, override patterns, inspectability, privacy boundaries.

### Specification Layer

`specs/`
Interface contracts and schema definitions.

### Runtime Layer

`runtime/`
Scaffold containers for future implementation.

### Open Questions

`open-questions/`
Explicit unresolved architectural decisions.
