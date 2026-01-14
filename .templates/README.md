# Daily Standup Reports - Documentation

## Overview

This repository contains daily standup reports for tracking team progress and activities. To maintain consistency and reduce duplication, we've created standardized templates and references.

## Quick Start

### For Formatted Reports
1. Copy `.templates/daily-standup-template.md`
2. Rename it with today's date (e.g., `2026-01-15.md`)
3. Fill in the relevant sections
4. Remove sections not applicable for the day

### For Quick Notes
1. Copy `.templates/simple-standup-template.md`
2. Rename it with today's date (e.g., `15-01-26.md`)
3. Fill in using the simple `y:` and `t:` format
4. Keep team names consistent

## Best Practices

### 1. Use Consistent Team Names
Always use the standard team names from `.templates/team-reference.md`:
- ✅ **Correct**: `### BoltPro Team` or `boltpro:`
- ❌ **Avoid**: `BoltPro team`, `bolt pro`, `BOLTPRO`

### 2. Use Standard Time Markers
Choose one format and stick with it:
- **Formatted style**: `**✅ Yesterday**` and `**📌 Today**`
- **Simple style**: `y:` and `t:`

### 3. Organize by Team Categories
Group teams logically:
1. Business Team
2. Technical Teams (BoltPro, BoltZyme, BoltChem, RNA Bolt, ReBolt, PCB Bolt)
3. Platform Teams (Agents, DevOps, QA)
4. Individual Contributors

### 4. Include All Relevant Sections
For each team/person, include:
- Yesterday's accomplishments
- Today's planned tasks
- Issues/blockers (if any)

### 5. Keep It Concise
- Use bullet points
- Be specific but brief
- Focus on outcomes and deliverables

## Template Files

### 📄 daily-standup-template.md
Full-featured template with:
- Markdown headers with emojis
- Organized sections for all teams
- Space for notes and follow-ups
- Professional formatting

**Use when**: Creating formal daily standup reports, preparing for meetings

### 📄 simple-standup-template.md
Lightweight template with:
- Simple `y:` and `t:` markers
- Quick note-taking format
- Minimal formatting

**Use when**: Taking quick daily notes, informal updates

### 📄 team-reference.md
Reference guide containing:
- Standard team names and descriptions
- Common abbreviations
- Emoji legend
- Naming conventions

**Use when**: Need to verify team names, understand abbreviations

## File Naming Conventions

Use consistent date formats:
- **Formatted reports**: `YYYY-MM-DD.md` (e.g., `2026-01-15.md`)
- **Simple notes**: `DD-MM-YY.md` (e.g., `15-01-26.md`)

## Common Patterns to Avoid

### ❌ Duplicate Headers
Don't repeat team headers multiple times in the same file:
```markdown
# Wrong
harsha:
...
harsha:
...
```

### ❌ Inconsistent Naming
Use consistent capitalization and spelling:
```markdown
# Wrong
Boltchem:
BoltChem:
boltchem:

# Correct
BoltChem:
```

### ❌ Mixing Formats
Don't mix formatted and simple styles in the same file:
```markdown
# Wrong
### **Harsha**
**✅ Yesterday**
...
mahek:
y:
...
```

## Examples

### Example 1: Formatted Report
See [example-daily-standup.md](example-daily-standup.md) for a complete example of a formatted daily standup report.

Key features:
- Professional markdown formatting with emojis
- Clear section headers for each team
- Organized Yesterday/Today/Issues structure
- Space for notes and follow-ups

### Example 2: Simple Notes
See [example-simple-standup.md](example-simple-standup.md) for a complete example of a simple standup report.

Key features:
- Quick `y:` and `t:` markers
- Minimal formatting for fast note-taking
- Consistent team organization
- Brief and to the point

## Benefits of Using Templates

1. **Consistency**: All reports follow the same structure
2. **Efficiency**: No need to recreate headers and sections
3. **Clarity**: Standardized format makes reports easier to read
4. **Maintainability**: Updates to templates propagate to new reports
5. **Reduced Duplication**: Common elements defined once in templates

## Migration Guide

If you have existing reports in different formats:

1. **Keep existing reports as-is** - No need to modify historical data
2. **Use templates for new reports** - Start using templates for all new standup reports
3. **Gradually standardize** - When updating old reports, consider migrating to the template format

## Questions?

For questions or suggestions about the templates, please refer to:
- `.templates/team-reference.md` for team names and conventions
- This document for usage guidelines
- Existing well-formatted reports (e.g., `09-12-25.md`, `10-12-25.md`) for examples
