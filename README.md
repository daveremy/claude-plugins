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
| [function-health-mcp](https://github.com/daveremy/function-health-mcp) | Query Function Health lab results, track biomarker changes, and get health recommendations | 0.5.3 |
| [apple-health-mcp](https://github.com/daveremy/apple-health-mcp) | Query Apple Health daily metrics, workouts, and trends via Health Auto Export CSVs | 0.1.0 |
| [hevy-mcp](https://github.com/daveremy/hevy-mcp) | MCP server for the Hevy fitness tracking API — workouts, routines, exercises, and more | 0.1.0 |
| [markviewz](https://github.com/daveremy/Markviewz) | Open .md files in a native macOS markdown viewer from Claude Code | 0.1.0 |

## Marketplace vs Direct Install

**Use this aggregated marketplace** when you want access to multiple daveremy plugins through a single marketplace entry.

**Use direct repo install** if you only need one specific plugin:

```
/plugin marketplace add daveremy/function-health-mcp
/plugin install function-health-mcp@function-health-mcp-plugins
```

Both approaches install the same plugin from npm — the difference is just how the marketplace is organized.
