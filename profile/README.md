# Statewright

State machine guardrails for AI agents. We build tools that enforce disciplined execution — controlling which tools your agent can use in each phase, at the protocol layer.

**[statewright.ai](https://statewright.ai)**

## Projects

### [statewright](https://github.com/statewright/statewright)

The core product. A Rust engine + managed cloud service that constrains AI coding agents via per-state tool enforcement, edit guards, command whitelists, and approval gates. Ships as plugins for Claude Code, Codex, Cursor, opencode, and Pi.

### [pg-pocketbase](https://github.com/statewright/pg-pocketbase)

PostgreSQL backend for PocketBase. Not a fork — a surgical overlay using Go build tags. Swaps SQLite for Postgres without patching upstream, giving you concurrent writes, multi-instance LISTEN/NOTIFY sync, and advisory-lock cron dedup. Tracks upstream releases cleanly.

---

Apache 2.0, portions FSL (statewright · MIT (pg-pocketbase)
