# ES 9.x Migration Dashboard

Interactive requirements tracker for the Elasticsearch **8.x → 9.4.2** migration (HNSW / nested `dense_vector`, semantic matching on C3/C4).

## View the dashboard

| Version | URL | Purpose |
|---------|-----|---------|
| **V1** | [index.html](./index.html) · [Live](https://wi-rajeev-ranjan.github.io/es-9-migration-dashboard/) | Full migration tracker — HLD, adapter writes, matching engine tab, Q&A |
| **V2** | [v2/index.html](./v2/index.html) · [Live V2](https://wi-rajeev-ranjan.github.io/es-9-migration-dashboard/v2/) | Brainstorm workspace — ideas, open questions, decision log (localStorage) |

Open either HTML file in a browser. No build step required.

## Contents

| File | Description |
|------|-------------|
| `index.html` | V1 — full interactive dashboard |
| `v2/index.html` | V2 — lightweight brainstorm board for next-iteration ideas |
| `hld-01-architecture.svg` | Target architecture & data flow |
| `hld-02-roadmap.svg` | Phase roadmap |
| `hld-03-migration-window.svg` | P2 freeze / reindex window |
| `hld-04-dualwrite-flow.svg` | Dual-write & 404 backfill flow |
| `ES9_Migration_Dashboard.pdf` | Static PDF snapshot (default tab only) |

## Offline use

Download this repo as ZIP from GitHub, or use `es-9-migration-dashboard.tar.gz`, then open `index.html` locally. No build step required.

## Tabs

- **migration_v0** — Committed HLD path (3M MAU first, experiment reads on C3/C4)
- **migration_v1** — Draft alternative (full copy, read-fallback)
- **write_consolidation** — P1 single-consumer decision analysis
