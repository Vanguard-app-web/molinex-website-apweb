# Graph Report - molinex-website-apweb  (2026-10-09)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 9 nodes · 10 edges · 2 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `ff3b04b6`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- script.js
- setLanguage

## God Nodes (most connected - your core abstractions)
1. `setLanguage()` - 3 edges
2. `loadTranslations()` - 2 edges
3. `text()` - 2 edges
4. `form` - 1 edges
5. `menu` - 1 edges
6. `menuToggle` - 1 edges
7. `status` - 1 edges
8. `T` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (2 total, 0 thin omitted)

### Community 0 - "script.js"
Cohesion: 0.33
Nodes (5): form, menu, menuToggle, status, T

### Community 1 - "setLanguage"
Cohesion: 0.67
Nodes (3): loadTranslations(), setLanguage(), text()

## Knowledge Gaps
- **5 isolated node(s):** `form`, `menu`, `menuToggle`, `status`, `T`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `setLanguage()` connect `setLanguage` to `script.js`?**
  _High betweenness centrality (0.018) - this node is a cross-community bridge._
- **What connects `form`, `menu`, `menuToggle` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._