# Atlas Catalog Repository

This repository contains skills, MCPs, tools, and configurations for Atlas.

## Structure

```
org/                          # Organization-wide (visible to everyone)
    claude.md                 # Org configuration
    skills/                   # Shared skills
    mcps/                     # Shared MCP servers
    tools/                    # Shared tools

teams/{team-uuid}/            # Team-specific (visible to team members)
    claude.md                 # Team configuration
    skills/                   # Team skills
    mcps/                     # Team MCPs
    tools/                    # Team tools

users/{user-uuid}/            # Personal (visible only to that user)
    claude.md                 # User configuration
    skills/                   # Personal skills
    mcps/                     # Personal MCPs
    tools/                    # Personal tools
```

## Visibility Rules

- `org/*` - Visible to all authenticated users
- `teams/{id}/*` - Visible only to members of that team
- `users/{id}/*` - Visible only to that specific user

## File Format

Each skill, MCP, or tool is a markdown file with:
- Title (H1)
- Description
- Usage instructions
- Configuration (if applicable)
