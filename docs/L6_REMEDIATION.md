# L6 remediation plan: first evidence-backed release

Tracks #34.

## Release gate

Before creating `v0.1.0`, record the target commit, dependency/security-check results, test results, and the exact command or workflow used to build any published artifact.

## Required evidence

- [ ] CI and test results tied to the release commit.
- [ ] Dependency and secret/security checks reviewed.
- [ ] Dataset and model artifact provenance recorded; no sensitive loan data included.
- [ ] Release notes state intended use and limitations, including that it is not credit-decisioning guidance.
- [ ] Rollback path: identify the previous commit/tag and the artifact to withdraw or supersede.

## Promotion boundary

Use a non-production environment and synthetic or approved non-production data for validation. A release denotes a reproducible repository state; it does not itself prove a production credit-risk service.
