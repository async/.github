# Async

Async builds tools for rapid prototype-to-prod development.

The goal is to make early ideas fast to sketch, easy to inspect, and realistic enough to grow. Start with local examples, JSON fixtures, tiny runtimes, async handlers, and signal-driven projections; then move toward typed APIs, durable state, production workflows, multi-team delivery, and agentic interfaces without throwing the prototype away.

## Projects

| Project | Stage | What it is | Use it for |
| --- | --- | --- | --- |
| [db](https://github.com/async/db) | Alpha | Gradual data workflow from JSON fixtures to generated types, local APIs, writable stores, and real persistence. | Move from local prototype data to typed APIs and durable state in small steps. |
| [web](https://github.com/async/web) | Experimental | Web app, router, and Request -> Response runtime packages for composing browser, API, edge, and data-backed apps. | Start with `@async/web`, then drop to router or runtime layers when routing, placement, cache behavior, or provider hooks need more control. |
| [pipeline](https://github.com/async/pipeline) | Beta | Local-first TypeScript pipeline engine for typed task graphs, run evidence, cache inputs, and thin generated GitHub Actions workflows. | Run the same verification workflow on a laptop and in CI while keeping workflow logic inspectable in `pipeline.ts`. |
| [framework](https://github.com/async/framework) | Experimental | Signal-based framework experiments for reactive web apps, custom elements, async handlers, and runtime-first UI. | Explore delegated `on:<event>` handlers, local and remote handler registries, resumability experiments, and signal-based projections. |
| [framework-demo](https://github.com/async/framework-demo) | Demo | Public demos and runtime examples for the framework work. | See the framework ideas in running examples before pulling the pieces into a real app. |

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
