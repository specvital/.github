# Architecture Decision Records (ADR)

> 🇰🇷 [한국어 버전](../../docs.kr/adr/README.md)

Documentation of architectural decisions made in the Specvital project.

## What is an ADR?

An Architecture Decision Record (ADR) captures an important architectural decision made along with its context and consequences. ADRs help maintain decision history across multi-repository microservices.

## When to Write an ADR

| Category         | Examples                                                |
| ---------------- | ------------------------------------------------------- |
| Technology Stack | Framework selection, library adoption, version upgrades |
| Architecture     | Service boundaries, communication patterns, data flow   |
| API Design       | Endpoint structure, versioning strategy, error handling |
| Database         | Schema design, migration strategy, indexing approach    |
| Infrastructure   | Deployment platform, scaling strategy, monitoring       |
| Cross-cutting    | Security, performance optimization, observability       |

## Templates

| Template                     | Use Case                        |
| ---------------------------- | ------------------------------- |
| [template.md](./template.md) | Standard ADR for most decisions |

## Naming Convention

```
XX-brief-decision-title.md
```

- `XX`: Two-digit sequential number (01, 02, ...)
- Lowercase with hyphens
- Brief and descriptive titles

## Technical Areas

| Area           | Affected Repositories |
| -------------- | --------------------- |
| Parser         | core                  |
| API            | web                   |
| Worker         | collector             |
| Database       | infra                 |
| Infrastructure | infra                 |
| Cross-cutting  | multiple              |

## ADR Index

| #   | Title         | Area | Date |
| --- | ------------- | ---- | ---- |
| -   | (No ADRs yet) | -    | -    |

## Process

1. **Create**: Copy [template.md](./template.md) → `XX-title.md`
2. **Write**: Fill in all sections with finalized decision
3. **Localize**: Create Korean version in `docs.kr/adr/`
4. **Review**: Submit PR for team review
5. **Merge**: Add to index after approval

## Related Repositories

- [specvital/core](https://github.com/specvital/core) - Parser engine
- [specvital/web](https://github.com/specvital/web) - Web platform
- [specvital/collector](https://github.com/specvital/collector) - Worker service
- [specvital/infra](https://github.com/specvital/infra) - Infrastructure
