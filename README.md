# OrbitOps - Amazon AI Operations Assistant

Evidence-driven Amazon operations analysis workspace built for portfolio demonstration.

## MVP capabilities

- Product, competitor, review, pain point, keyword, listing and strategy agents
- Review CSV/JSON import with local-only processing
- Evidence trace from operational insight back to source review
- Structured keyword prioritization without invented search volume
- Listing audit and generation workspace
- Human approval gate before publishing copy
- JSON report export
- Responsive desktop and mobile interface

## Run locally

Open `index.html` directly in a browser, or serve the directory with any static web server.

## Design principles

1. Facts, inferences and recommendations are separated.
2. Unknown data remains `null` instead of being estimated as fact.
3. Every important insight has traceable evidence.
4. Deterministic calculations are not delegated to an LLM.
5. Human review remains required for product claims, compliance and publishing.

The detailed GitHub research, prompt architecture, schemas and development roadmap are available in [`outputs/amazon-ai-operations-assistant-research-design.md`](outputs/amazon-ai-operations-assistant-research-design.md).

## Status

This repository currently contains the interactive, no-API-key MVP. A model-provider adapter and persistent backend are planned for the next phase.
