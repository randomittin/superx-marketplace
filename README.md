# superx marketplace

Plugin marketplace for [superx](https://github.com/randomittin/superx) — autonomous superskill manager for Claude Code.

## Install

```bash
# Add this marketplace (one-time)
claude plugins marketplace add randomittin/superx-marketplace

# Install superx
claude plugins install superx
```

## What you get

**superx** turns a single prompt into a finished project:
- Decomposes work, spawns parallel agents, enforces quality gates
- Real-time pixel-art dashboard with isometric city map, war room, streaming logs
- Single-phase orchestration — Claude runs end-to-end, only asks when it actually needs you
- Auto-checkpoint git commits, session history, conversation continuity via `--resume`

Requirements: Claude Code 1.0+, Python 3.11+ (stdlib only), Git.

See the [full README](https://github.com/randomittin/superx) for architecture, setup, and troubleshooting.

## Update

```bash
claude plugins update superx
```

## License

MIT
