# Telemetry Atlas — Project Charter

## Objective

A catalog and inspection surface for telemetry event types, provenance, state changes, integrity fields, and retention classifications.

## Current state

Initial scaffold. The event schema below adapts the existing SOVRINT observability record fields; this repository has no production telemetry source.

## Initial scope

- Define the domain vocabulary and component boundaries.
- Record source lineage, versioning, evidence class, and validation status.
- Develop reviewable specifications and synthetic examples before implementation.
- Link the work to existing SOVRINT registries rather than duplicating canonical definitions.

## Out of scope for this initial scaffold

- Claims that the system is deployed or operational.
- Claims of empirical validation without a documented method and evidence.
- Reinterpretation or promotion of unverified equations or symbols.
- Collection of personal, sensitive, or production data.

## Dependencies

Observability, Telemetry & Audit Spine; runtime topology; synthetic validation traces.

## Completion checks for an initial release

- Each file has an author, date/version, and provenance note.
- Synthetic and observed material are visibly distinguished.
- Schemas validate example records and reject missing provenance fields.
- Rights and third-party notices remain intact.

## Source status

This project scaffold uses the repository’s registered project name and available first-party SOVRINT architecture material. Any additional project-specific structure introduced here is a proposal pending canonical review.
