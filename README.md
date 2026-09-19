# AdviceKit

AdviceKit is an open-source Python toolkit for building evidence-aware financial-advice software.

It helps applications turn transcripts, notes, documents, and provider records into sourced observations, explicit unknowns and conflicts, review items, and draft fact-finds. Generated output remains proposed until an authorised person reviews it.

This repository is at the design and bootstrap stage. Public interfaces are not yet stable.

The TypeScript implementation lives in [ChunkbaseAI/advicekit-js](https://github.com/ChunkbaseAI/advicekit-js).

## What belongs here

- Stable Python contracts for evidence, observations, review, and draft advice records
- Validation and transformation tools that do not hide uncertainty
- Provider adapters that preserve provider-native identifiers and unsupported fields
- Tests and fixtures that demonstrate the same behaviour as AdviceKit JS

## What does not belong here

- Autonomous financial advice or suitability decisions
- Silent writes to authoritative client records
- Chunkbase's private evaluation and production workflow logic
- Tutorial collections and architecture demonstrations, which belong in `financial-advice-ai`

## Licence

Apache License 2.0. See [LICENSE](./LICENSE).

## Contributing

Read [AGENTS.md](./AGENTS.md), [CONTEXT.md](./CONTEXT.md), and [CONTRIBUTING.md](./CONTRIBUTING.md) before making a change.
