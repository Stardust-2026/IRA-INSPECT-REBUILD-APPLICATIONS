# Compact work records

Use these structures in the existing project documentation or a small report. Keep only sections appropriate to scope.

## Brief

- Target and capture date/revision:
- Goal and selected workflow:
- Roles and access available:
- Fidelity and target stack:
- Required acceptance criteria:
- Proposed improvements and scope assumptions:

## Evidence ledger

| ID | Screen/action/source location | Finding | Classification | Coverage/limitation |
| --- | --- | --- | --- | --- |
| E01 | Concrete screenshot, source line, or sanitized capture reference | Narrow factual claim | Observed / source candidate / inferred / proposed / unknown | Role, state and scope |

Keep evidence references resolvable. Do not write fictitious evidence IDs as if capture files exist. Distinguish directly inspecting source from inferring implementation from behavior.

## Workflow and contract record

| Initial state and role | Action | Observed result | Request/response shape | Evidence or unknown |
| --- | --- | --- | --- | --- |

Document preconditions, state changes and failure paths. Label the proposed data model separately from any actually recovered schema.

## Improvement backlog

| Priority | Observed problem | Proposed change | Expected benefit | Acceptance criterion | Dependency/effort range |
| --- | --- | --- | --- | --- | --- |

## Verification matrix

| Criterion | Original evidence | Rebuild check | Result | Gap or intentional difference |
| --- | --- | --- | --- | --- |

Use pass, fail, unknown, or intentionally changed. State when no original was available for comparison. Separate functional, visual, accessibility, and operational checks. Do not convert unknown checks into passes or include them in an invented fidelity score.

## Resume checkpoint

Record the working path and revision, scope, evidence locations, decisions, implementation status, tool limitations, failed/unknown checks and next action. Exclude credentials and sensitive source data. Keep this record with the project, not inside the reusable skill.
