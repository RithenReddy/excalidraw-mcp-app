# Origin

This repository is a copy of the official Excalidraw MCP App Server for hosting experiments.

- Upstream: https://github.com/excalidraw/excalidraw-mcp
- Upstream commit mirrored: `157aa23ceb1976008aadc89eb05e3444060f09d6` (main as of 2026-07-12)
- License: MIT (see upstream)
- Official remote: https://mcp.excalidraw.com

Docs assets `docs/demo.gif` and `docs/logo.png` were intentionally omitted from this initial push because of binary size limits in the GitHub MCP file writer. Re-add them from upstream if needed:

```bash
git remote add upstream https://github.com/excalidraw/excalidraw-mcp.git
git fetch upstream
git checkout upstream/main -- docs/demo.gif docs/logo.png
```
