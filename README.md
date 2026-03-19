# polydev-marketplace

Claude Code plugin marketplace configuration for the polydev ecosystem.

## Plugins

| Plugin | Description |
|--------|-------------|
| [polydev](https://github.com/shikihane/polydev) | Parallel development orchestration with Git worktrees, terminal sessions, and background agents |
| [poly-retrace](https://github.com/shikihane/poly-retrace) | Claude Code session history search and analysis with SQLite FTS5 |

## Installation

### 1. Add the marketplace

```bash
claude plugin marketplace add https://github.com/shikihane/polydev_marketplace
```

### 2. Install plugins

```bash
# Install both plugins
claude plugin install polydev@polydev-marketplace
claude plugin install poly-retrace@polydev-marketplace
```

Or install a specific plugin:

```bash
claude plugin install polydev@polydev-marketplace
claude plugin install poly-retrace@polydev-marketplace
```
