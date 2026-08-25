---
name: hermes-skill-architecture-diagram
description: Create dark, readable SVG architecture diagrams from system descriptions. Use when a user asks for this workflow or a closely related task.
---

# Architecture Diagram

Create deterministic dark-themed SVG architecture diagrams from a system description, repository, or deployment plan.

## Workflow

1. Extract actors, services, stores, protocols, trust boundaries, and deployment locations.
2. Normalize names and remove secrets, private hostnames, and personal identifiers.
3. Choose the smallest useful diagram: topology, sequence, data flow, or deployment.
4. Render SVG with readable labels, consistent arrows, and a dark background.
5. Validate that every connection has a source, destination, and direction.
6. Deliver the SVG plus a short legend and any assumptions.

Prefer explicit evidence over guessed infrastructure. Mark unknowns as unknown.
