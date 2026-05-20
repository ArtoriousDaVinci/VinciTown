# VinciTown

## GitHub DNA: Source-of-Truth Policy

This repository is the durable system of record for implementation truth.

- **GitHub is authoritative for artifacts and evidence**: code, configs, tests, and commit history are the proof surfaces.
- **Linear is authoritative for coordination**: prioritization, assignment, and operational command tracking.
- **Conflict rule**: if Linear metadata and repository state differ, repository state in GitHub governs implementation truth.
- **Validation rule**: readiness claims require committed artifacts and executable test evidence in GitHub.
- **Boundary rule**: Linear cannot grant authority over live trading, capital deployment, readiness, or profitability.

## Operating Expectations

1. Land changes through commits and pull requests.
2. Keep verification attached to code changes (test output, checks, and review history).
3. Treat issue tracker updates as planning/control signals, not implementation evidence.

These guardrails preserve Merlin DNA by ensuring non-live operational decisions remain auditable and reproducible from repository history.
