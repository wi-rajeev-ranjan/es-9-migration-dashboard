# ES 9.x Migration Dashboard

Interactive requirements tracker for the Elasticsearch **8.x → 9.4.2** migration (HNSW / nested `dense_vector`, semantic matching on C3/C4).

## View the dashboard

Open **[index.html](./index.html)** in a browser, or use GitHub Pages (if enabled):

**Live:** https://workindia-private.github.io/es-9-migration-dashboard/

## Contents

| File | Description |
|------|-------------|
| `index.html` | Full interactive dashboard — migration_v0 (HLD), migration_v1 (draft), write_consolidation tab, Q&A |
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
