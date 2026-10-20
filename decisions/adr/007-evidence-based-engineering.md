---
title: ADR-007 Evidence-Based Engineering
owner: CEO
status: Accepted
last_updated: 2026-10-20
---

# Evidence-Based Engineering adoption

## Context and authority

On 2026-10-20 Pedro explicitly requested implementation of the user-approved Evidence-Based Engineering policy across Polaris, Axis, Sentinel and relevant Constellation agents/skills. This records approval of the scoped operational policy, not an amendment to the philosophical canon or authority to merge, release, deploy or configure providers.

The policy derives from constitutional principles Context governs, Evidence over intuition, AI agency boundaries and Documentation is part of the system, and laws of Context, Evidence, Reversibility, Explicit Ethics, Boundaries and Architectural Memory. The existing Constitution remains authoritative and unchanged.

## Decision and ownership

Polaris owns adoption, coordination and evidence/authority gates through [operating rules](../../PROJECT_RULES.md) and [composition](../../integration/README.md). Axis owns the engineering method in its guide `guides/evidence-based-engineering.md`. Sentinel owns security-specific requirements in its `guidance/project-context.md`. Constellation's workflow and optional native profiles apply those owners' guidance to the actual product. Main-branch discovery links do not establish a reviewed revision; record source revisions used for execution.

Apply local-first verification before remote/shared publication; Docker-first for compatible work with native Apple and justified contextual exceptions; small reversible increments; observable acceptance criteria; risk-scaled tests; secure defaults; reproducible environments; CI gates; proportionate observability; durable significant decisions; evidence-backed reporting. Local commits remain distinct from remote publication and merge/release. Standalone Axis or Sentinel use does not adopt Polaris implicitly.

## Alternatives and consequences

Copying a full policy into every role would drift. Requiring Docker for all work would reduce fidelity for Apple development and add ceremony for documentation changes. Relying only on CI would move avoidable failures beyond the local verification boundary. The selected approach keeps reusable details with their owners, uses short entry-point references, preserves stronger adopted constraints and requires explicit disclosure/authorisation for blocked publication prerequisites.

No additional framework, provider, runtime service, schema or mandatory evidence template is introduced. Required GitHub checks and branch protections must be verified independently; this policy does not configure them. Merge of the review changes remains a separate gate. Revisit if real project evidence shows excess cost, missing coverage or ambiguity; flag exact contrary ratified text before proposing an amendment.
