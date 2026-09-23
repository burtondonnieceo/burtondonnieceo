# Ecosystem engineering catalog

Reviewed September 23, 2026. This index distinguishes public explanations, locally validated extracts, work that needs stabilization, private products and historical material. Repository files, catalog entries and working tools are different units; this index does not combine them into a tool count.

## Prepared toolkit

Four local tools have been extracted into one coherent Python package with no runtime dependencies beyond the standard library. The package is prepared and tested locally; source publication awaits the owner's choice of reuse license.

| Tool | Concrete behavior | Validation and limit |
| --- | --- | --- |
| Decision review | Preserves proposals, receipt-backed checks, independent reviews, complaints and linked corrections | 15 regression tests; records actions but never executes them |
| Event outbox | Atomically stores an event and pending row; exact retries count once; conflicting retries fail | 16 regression tests; no sender, billing or blockchain-delivery adapter |
| Skill Hub | Searches public GitHub skills, pins quarantined content and records review and use | 56 regression tests; review metadata is not a safety certificate |
| Audience records | Campaign-scoped imports, evidence fields, durable opt-outs and separate registration counts | 22 regression tests; local records and review exports only |

Three additional tests verify offline examples, absence of private commands and standard-library runtime imports. All 112 tests passed in a fresh Windows Python 3.11.9 environment. The built package also installed successfully into that environment. Cross-platform CI is prepared but has not run publicly while source is held.

Read the [decision-history explainer](docs/decision-history.md), [skill-provenance explainer](docs/skill-provenance.md) and [publication status](docs/publication-status.md).

## Extraction or stabilization candidates

| Area | Useful work recovered | Why it is held |
| --- | --- | --- |
| Public-site diagnostics | Bounded identity/release checks and separate completeness predicates | Site-specific configuration needs a portable schema and fresh adversarial tests |
| Multisite operations monitor | Scheduled observations, incident state and recovery evidence | Scheduling, notification routes and live-site assumptions are environment-specific |
| Plugin capability registry | Separates catalog selection from implemented, authorized runtime access | Catalog provenance and adapter contracts require their own review; catalog size is not runtime capability |
| Owner-to-Codex runner | Durable job, cancellation and restart work | Active development; excluded from public extracts |
| Private mobile operations console | Owner controls and mobile presentation | Authentication and end-to-end access require separate validation |
| Audience production adapter | Reads a configured authoritative registration source | Private account/database binding; the portable extract includes only local records |
| Synthetic action queue | Quote-bound approval, separate execution, exact retries and emergency stop | Needs a standalone simulation threat review and sanitized package; no live finance claim |
| Webhook signature boundary | Raw-body verification before a downstream handler | Provider compatibility and application integration need scoped review |
| Release identity and manifests | Separates source, publication and deployed-artifact evidence | Existing receipts contain private local/provider details |
| Approved avatar workflow | Tracks identity, accepted voice source and performance review | Personal media rights and provider dependencies need a separate publication decision |

## Products and private scope

Nucleus, NOAH and Internet of Intelligence are the application environment from which these patterns came. Parlay and DonnieBurton.com remain separate products. Their public interfaces do not establish that every integration or service is active, and this GitHub publication does not change their deployments.

Prudent healthcare/staffing work, Solomon financial workflows and client projects require product-specific rights, privacy and source review before extraction. Patient and customer data, legal drafts, investor materials, wallet and settlement records, private research, credentials and commercial application cores are excluded.

Legacy modules cover mission planning, model routing, memory, knowledge retrieval, agent coordination, reporting, desktop bridges and business operations. Much of that work depends on the wider private runtime. A source file is not automatically a portable public API.

## Historical and third-party work

[AIIP-IOB-MVP](https://github.com/burtondonnieceo/aiip-iob-mvp) is a historical architecture document. At review its public default branch contained only a README. No runnable gateway, translator, ledger or console was present there. An original early AI-to-AI milestone receipt has not been recovered for this publication; later demonstrations are not used to establish a first-message date or a priority claim.

Third-party skills, provider plugins and upstream frameworks retain their authorship and licenses. They are not presented as Donnie-authored tools and are not redistributed here. The prepared Skill Scout instruction is a portable adaptation of the first-party provenance workflow.
