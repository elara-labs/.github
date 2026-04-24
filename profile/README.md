<p align="center">
  <img src="https://rajkumarsakthivel.github.io/elara/logo.svg" alt="Elara" width="200">
</p>

<h1 align="center">Elara</h1>

<p align="center">
  <strong>Build Intelligent Systems.</strong>
</p>

<p align="center">
  AI solutions that automate workflows, improve decision making, and enable business scalability.
</p>

---

## What We Do

We create intelligent applications across three core areas:

- **AI Automation** : Intelligent systems that automate repetitive processes and adapt over time.
- **Custom AI Apps** : Tailored solutions including decision engines and intelligent interfaces.
- **Scalable Systems** : Observable, resilient infrastructure designed for growth.

## Projects

### [Claude Context Engine](https://github.com/fazleelahhee/Claude-Context-Engine)

A local first context management system that optimizes how Claude AI processes code repositories. It indexes projects, breaks code into semantic chunks, and retrieves only the relevant context for each task.

**Key highlights:**

- Semantic chunking with tree-sitter for meaningful code units (functions, classes, modules).
- Hybrid retrieval combining vector search (sqlite-vec) and BM25 keyword matching (SQLite FTS5).
- Graph aware expansion that follows import and call relationships automatically.
- Cross session memory for architectural decisions and code areas.
- ~70% token savings through targeted retrieval vs full file pasting.
- MCP integration exposing 9 tools for Claude Code via Model Context Protocol.
- Web dashboard for monitoring index status, token usage, and past sessions.

**Tech stack:** Python 3.11+, sqlite-vec, SQLite FTS5, BAAI/bge-small-en-v1.5 (ONNX Runtime), tree-sitter, FastAPI.

```bash
uv tool install claude-context-engine
cd /path/to/your/project
cce init
```

## Get in Touch

Interested in working with us? [Contact us](mailto:hello@yourdomain.com).
