# polydev-marketplace

Claude Code plugin marketplace configuration for the polydev ecosystem.

## Plugins

| Plugin | Description |
|--------|-------------|
| [polydev](https://github.com/shikihane/polydev) | Parallel development orchestration with Git worktrees, terminal sessions, and background agents |
| [poly-retrace](https://github.com/shikihane/poly-retrace) | Claude Code session history search and analysis with SQLite FTS5 |

## Installation

### 1. Add the marketplace

```
/plugin marketplace add shikihane/polydev_marketplace
```

### 2. Install plugins

```
/plugin install polydev@polydev-marketplace
/plugin install poly-retrace@polydev-marketplace
```

### 3. Reload plugins

```
/reload-plugins
```
