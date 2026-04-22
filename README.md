# Crux Marketplace

A Claude Code plugin marketplace by The Crux Digital Team.

## Plugins

| Plugin | Description |
|--------|-------------|
| **glados** | GLaDOS — agentic development framework with structured workflows, modules, and personas |
| **relay-ds** | Automated Design System. Agent-team pipeline that turns a Figma component into a production React component via Understand → Build → Verify phases, with pluggable design-system adapters and structured human gates. |

## Installation

### 1. Add the marketplace

In Claude Code, run:

```
/plugin marketplace add cruxdigital-llc/crux-marketplace
```

Or add it manually to your `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "crux-marketplace": {
      "source": {
        "source": "github",
        "repo": "cruxdigital-llc/crux-marketplace"
      }
    }
  }
}
```

### 2. Install a plugin

```
/plugin install glados@crux-marketplace
```

### Team setup

To automatically prompt all team members to add this marketplace, add the `extraKnownMarketplaces` config above to your project's `.claude/settings.json` instead of the user-level file.
