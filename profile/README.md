# Unified Product Graph

**An open specification for structured product knowledge** — a typed, queryable graph that works with any MCP-compatible AI tool.

> 🧪 **Public beta.** UPG v0.6 is an early public beta — the spec and packages may still change. Issues and feedback are very welcome.

## Repositories

- **[spec](https://github.com/unified-product-graph/spec)** — the standard: the `.upg` file format, the entity & edge ontology, lifecycles, scales, and the framework catalog. This is what implementations build against.
- **[tools](https://github.com/unified-product-graph/tools)** — the reference implementation: a programmatic SDK, the `upg` CLI, local + cloud MCP servers, import adapters, and the `.upg.md` renderer.

## Install

```bash
npx @unified-product-graph/cli           # the upg CLI
npx @unified-product-graph/mcp-server    # local MCP server — connect UPG to Claude Code / any MCP client
npm install @unified-product-graph/core  # the spec + TypeScript types
npm install @unified-product-graph/sdk   # programmatic read/write of .upg graphs
```

## Learn more

- **Docs & spec:** https://unifiedproductgraph.org
- **npm:** https://www.npmjs.com/org/unified-product-graph
