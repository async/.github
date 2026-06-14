# Async

Async builds tools for rapid prototype-to-prod development.

The goal is to make early ideas fast to sketch, easy to inspect, and realistic enough to grow. Start with local examples, JSON fixtures, tiny runtimes, async handlers, and signal-driven projections; then move toward typed APIs, durable state, production workflows, multi-team delivery, and agentic interfaces without throwing the prototype away.

## Projects

| Project | Stage | Site | What it is | Use it for |
| --- | --- | --- | --- | --- |
| [db](https://github.com/async/db) | Alpha | [Docs](https://async.github.io/db/) | Gradual data workflow from JSON fixtures to generated types, local APIs, writable stores, and real persistence. | Move from local prototype data to typed APIs and durable state in small steps. |
| [web](https://github.com/async/web) | Experimental | [Docs](https://async.github.io/web/) | Web app, router, and Request -> Response runtime packages for composing browser, API, edge, and data-backed apps. | Start with `@async/web`, then drop to router or runtime layers when routing, placement, cache behavior, or provider hooks need more control. |
| [pipeline](https://github.com/async/pipeline) | Beta | [Docs](https://async.github.io/pipeline/) | Local-first TypeScript pipeline engine for typed task graphs, run evidence, cache inputs, and thin generated GitHub Actions workflows. | Run the same verification workflow on a laptop and in CI while keeping workflow logic inspectable in `pipeline.ts`. |

## Helper Tools

| Tool | Site | What it is | Use it for |
| --- | --- | --- | --- |
| [dispatch](https://github.com/async/dispatch) | [Docs](https://async.github.io/dispatch/) | Installable local coordination CLI for goal-first async chat work, plan boards, runtime ledgers, workers, and receipts. | Keep broad async work explicit before it turns into repo edits, chats, or release handoffs. |
| [auto-git](https://github.com/async/auto-git) | [Docs](https://async.github.io/auto-git/) | AI agent Git workflow helpers for intent-based commits, release checks, and repository handoffs. | Split, verify, checkpoint, and land agent-assisted changes while preserving reviewable git intent. |
| [api-contract](https://github.com/async/api-contract) | [Docs](https://async.github.io/api-contract/) | API compatibility ledgers and impact checks for Async packages. | Track exported features and consumer usage so breaking API changes are caught before release. |
| [claims](https://github.com/async/claims) | [Docs](https://async.github.io/claims/) | Documentation-claim coverage checks for tests and AI-assisted release loops. | Keep README and docs promises anchored to source text and mapped to real tests. |

## Direction

We care about:

- Prototype speed without dead-end architecture.
- Runtime-owned state and explicit transitions for long-lived async workflows.
- Async handlers that keep UI intent small and composable.
- Signals and projections that make state changes visible without scattering workflow logic.
- Local-first examples and small runtimes that make behavior testable early.
- Gradual paths from demos and fixtures to production-shaped systems.
- Async multi-team parallel deployment as an evolving focus for shipping related workstreams without turning coordination into a bottleneck.

The current repos are still evolving, but the throughline is stable: build small tools that compress the distance between a working prototype, coordinated team execution, and production software.

The older `async-framework` organization is kept only for redirects and historical references.
