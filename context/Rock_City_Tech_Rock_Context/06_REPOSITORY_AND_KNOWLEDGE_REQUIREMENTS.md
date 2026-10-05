# Repository + Knowledge Requirements

## Canonical Context Repository
Known canonical Rock City context repository:
`nnaicker96/Rock-City-`
Branch: `main`

Where available, treat the canonical repository as versioned institutional context rather than rebuilding the same context from memory.

## Repository Purpose
Repositories should make work portable between:
- ChatGPT / AI systems;
- developers;
- designers;
- Notion;
- GitHub;
- future administrators.

## Preferred Context Pack Pattern
Use Markdown as the primary portable context format.

Recommended structure:
```text
/
├── START_HERE.md
├── 01_WORKING_PREFERENCES.md
├── 02_ROCK_CITY_CORE_CONTEXT.md
├── 03_MINISTRY_AND_TRANSFORMATION_CONTEXT.md
├── 04_TECH_ROCK_CONTEXT.md
├── 05_PLANNING_CENTER_ARCHITECTURE.md
├── 06_REPOSITORY_AND_KNOWLEDGE_REQUIREMENTS.md
├── 07_MEDIA_DESIGN_AND_VISUAL_SYSTEM.md
├── 08_PRODUCTION_AND_TECHNICAL_CONTEXT.md
├── 09_MINISTRY_OPERATIONS.md
├── 10_DIGITAL_SYSTEMS_AND_PROJECTS.md
├── 11_GOVERNANCE_DATA_AND_ACCESS.md
├── 12_CURRENT_CONTEXT_AND_CALENDAR.md
├── 13_NON_NEGOTIABLES_AND_FAILURE_MODES.md
└── CONTEXT_UPDATE_PROTOCOL.md
```

For larger repositories, split into:
```text
/core
/brand
/ministry
/systems
/projects
/current
/resources
/archive
```

## Repository Rules
- `START_HERE.md` must explain authority and reading order.
- Use clear filenames, not vague names like `notes-final-v2.md`.
- Keep stable context separate from current/project context.
- Archive obsolete context rather than leaving contradictions in active files.
- Explicit corrections must replace or clearly supersede older rules.
- Do not store secrets, passwords, API keys, tokens or private credentials in context files.
- Use `.env` / deployment secrets for credentials, never committed Markdown or source code.
- Document setup and dependencies.
- Maintain a changelog for meaningful architecture/context changes where the repository becomes operationally important.

## Source-of-Truth Principle
Different systems own different data:
- Planning Center: ministry/person/participation records.
- Google Drive: working documents and assets.
- GitHub: code/versioned technical/context artifacts.
- Notion/operations system: planning, knowledge, decisions and actionable work where adopted.

Do not create competing “truths” without a defined sync/ownership rule.

## Importability
Context should remain usable even outside GitHub. Prefer:
- Markdown;
- portable relative links;
- plain folder structures;
- no dependency on proprietary database formatting for critical institutional knowledge.
