# Contributing to Trivian Technologies

Thank you for your interest in contributing.

Trivian Technologies maintains repositories at different maturity levels, from research and experimental implementations to working alpha and deployable components. Before contributing, read the repository-specific README, license, tests, and governance notes.

## Before opening a pull request

- Open or reference an issue when the change is substantial.
- Keep changes narrow enough to review.
- Preserve historical provenance and existing adversarial or falsification evidence.
- Do not silently weaken authority, revocation, consent, provenance, dissent, or audit boundaries.
- Add or update tests when behavior changes.
- Document assumptions, unresolved questions, and known limitations.

## Relational invariants

TRIA is oriented by four Relational Constants:

- Reciprocity
- Embodiment
- Non-Domination
- Emergence

These are not decorative language. Where a repository implements governance or agent behavior, contributions should make their relationship to these invariants inspectable.

A recurring architectural distinction is:

> **Capability ≠ authority.**

A system's ability to perform an action does not establish that it is authorized to do so.

## Review expectations

Review may consider:

- correctness and test coverage;
- compatibility with the repository's current contract;
- authority and revocation behavior;
- provenance and auditability;
- failure modes and adversarial cases;
- effects on dissent, uncertainty, and revision;
- backward compatibility and migration requirements.

Repository-specific contribution rules take precedence where they are more restrictive.

## Security

Do not disclose suspected vulnerabilities in a public issue. Follow [SECURITY.md](SECURITY.md).

## Conduct

Participation in Trivian Technologies repositories is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
