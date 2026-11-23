# learning-MCP-servers

Follow the [build-server guide](https://modelcontextprotocol.io/docs/2026-07-28/develop/build-server)
and write the server code yourself in `typescript/src/index.ts` and `python/weather.py`.

## TypeScript

Prerequisite: Node.js 20 or higher.

```bash
cd typescript
npm install
npm run build
node build/index.js
```

## Python

Prerequisites: Python 3.10 or higher and [uv](https://docs.astral.sh/uv/).

```bash
cd python
uv sync
uv run weather.py
```
