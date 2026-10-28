# Cytoscape.js Agent Instructions

This file routes agent tasks to the correct domain to conserve context and prevent cross-domain hallucinations. Do not read the entire `src/` directory.

## Context Routing
- **Core math, collections, headless logic**: See `/src/core/AGENTS.md`
- **Layout algorithms**: See `/src/extensions/layout/AGENTS.md`
- **Canvas, UI, rendering**: See `/src/extensions/renderer/AGENTS.md`
- **Testing**: See `/test/AGENTS.md`

## Environment
- Use Node via `.nvmrc` (`nvm use`).
- Use `npm` (relies on `package-lock.json`).
- Source of truth is `src/`. Do not edit generated files in `build/`, `dist/`, or `documentation/`.
- Documentation source is `documentation/docmaker.json` and `documentation/md/`.