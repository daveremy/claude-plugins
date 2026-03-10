# daveremy Claude Code Plugins

Aggregated marketplace for all published daveremy Claude Code plugins.

## Quick Start

Add this marketplace to Claude Code (one time):

```
/plugin marketplace add daveremy/claude-plugins
```

Then install any plugin:

```
/plugin install function-health-mcp@daveremy-plugins
```

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [function-health-mcp](https://github.com/daveremy/function-health-mcp) | Query Function Health lab results, track biomarker changes, and get health recommendations | 0.5.1 |

## Marketplace vs Direct Install

**Use this aggregated marketplace** when you want access to multiple daveremy plugins through a single marketplace entry.

**Use direct repo install** if you only need one specific plugin:

```
/plugin marketplace add daveremy/function-health-mcp
/plugin install function-health-mcp@function-health-mcp-plugins
```

Both approaches install the same plugin from npm — the difference is just how the marketplace is organized.
