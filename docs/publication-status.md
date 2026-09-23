# Publication status

Snapshot: September 23, 2026.

The public materials in this profile are the engineering catalog and explainers. The first code package is prepared locally as `ecosystem-tools` version 0.1.0. Its source publication awaits the owner's reuse-license choice; no public package download, PyPI release or hosted demo is claimed.

## Prepared and checked

- Four local tools: decision review, event outbox, Skill Hub and Audience records.
- Python package metadata, CLI entry points, API reference, installation guide, architecture/trust model, change notes and contribution/security guidance.
- Four offline synthetic examples and 112 passing regression tests.
- A fresh Windows Python 3.11.9 virtual-environment run and successful wheel build/install.
- A separate allowlisted publication folder, source hashes and clean-history preparation.
- File-content checks for credential patterns, private local paths and broken relative documentation links, followed by scoped review. Pattern scans do not guarantee the absence of secrets.

The prepared CI matrix covers Windows and Ubuntu with Python 3.11 and 3.13, plus Ubuntu 3.14. It has not run publicly while source is held. The tests use synthetic data and mocks; they do not establish external delivery, production application correctness or an independent security audit.

## Release condition

Publishing code makes it visible but does not itself choose developers' reuse rights. No blanket open-source license was recovered for the first-party extracts. The owner is choosing between a permissive source license and a documentation-only release. Third-party packages, private applications, brand media and operational data remain outside that choice.

The source release will be linked here only after the license is recorded, the reviewed files are pushed and the exact public commit is verified. Application deployments follow their own release process.
