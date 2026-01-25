# Brain Path Projects

**Adaptive Work Loop (AWL) Project Management System**

This repository tracks projects through a structured state machine:

```
UNDERSTAND → ANALYZE → DECIDE → EXECUTE → VERIFY → LEARN
```

## Directory Structure

```
_active/          # Active projects
_archive/         # Completed/abandoned projects
_templates/       # Project templates by type
_strategy/        # Social posting guidelines
_social/          # Posted content archive
  ├── queue/      # Ready to post
  └── archive/    # Already posted
```

## Project Structure

Each project in `_active/` contains:

- `overview.md` - Project description, goals, milestones
- `events.md` - Activity log (append-only)
- `state.json` - Current state machine position
- `social_log.jsonl` - Today's social-worthy moments
- `artifacts/` - Output files, screenshots, etc.

## Complexity Tiers

| Tier | Name | Duration | Loop Used |
|------|------|----------|----------|
| 0 | ATOMIC | Seconds | None |
| 1 | QUICK | Minutes | OODA |
| 2 | STANDARD | 1-4 hours | Specialized |
| 3 | COMPLEX | Hours-days | Full AWL |
| 4 | ORCHESTRATED | Days-weeks | AWL + Sub-loops |

## Specialized Loops

- **INSTALL** - Deploy services
- **DEBUG** - Troubleshoot issues
- **RESEARCH** - Find information
- **CONFIG** - Change settings
- **DEPLOY** - Release changes
- **CONTENT** - Create content
- **OUTREACH** - Prospect/contact

---

*Managed by n8n workflows at n8n.millyweb.com*