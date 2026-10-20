---
title: Polaris contribution workflow
owner: Maintainer
status: Active
last_updated: 2026-10-20
---

# Contribution workflow

Inspect the affected repository's instructions and actual implementation before changing it. Use focused branches, conventional commits, observable evidence and proportional documentation. No automatic merge, release, deployment or external configuration.

Run the documentation validator and CLI regressions; add relevant behaviour checks for actual implementation changes. Keep secrets, generated caches and unrelated files out of commits. No general redistribution licence is selected by the extraction.

Before remote/shared publication, apply the local-first Evidence-Based Engineering requirements in [PROJECT_RULES.md](PROJECT_RULES.md). Use Docker where feasible or document the appropriate native/contextual alternative. Local checkpoints do not grant publication or merge authority; CI supplements local evidence.
