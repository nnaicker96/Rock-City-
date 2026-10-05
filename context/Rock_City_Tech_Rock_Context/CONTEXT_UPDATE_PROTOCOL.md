# Context Update Protocol

## Why This Exists
Rock City’s ministry, systems and projects evolve quickly. The context pack must stay authoritative without becoming a pile of contradictory history.

## Update Types

### 1. Stable Institutional Change
Examples:
- ministry ownership changes;
- permanent brand rule;
- Planning Center architecture decision;
- Tech Rock scope change.

Action:
- update the relevant core file;
- remove/supersede contradictory wording;
- record the change in a changelog if maintained.

### 2. Current Programme / Calendar Change
Examples:
- monthly campaign;
- service times;
- event date;
- temporary rollout phase.

Action:
- update `12_CURRENT_CONTEXT_AND_CALENDAR.md`;
- do not rewrite stable context unless the underlying model changed.

### 3. Project-Specific Brief
Examples:
- poster;
- website;
- Kids Rock workbook;
- event programme.

Action:
- keep in `/projects/<project-name>/`;
- reference stable context rather than duplicating it;
- archive when complete.

### 4. Correction
When the user explicitly says an existing fact is wrong:
- treat the correction as authoritative;
- replace the old active statement;
- do not keep both as if equally valid.

## Suggested Metadata for Project Files
```yaml
project:
status:
owner:
created:
last_updated:
source_of_truth:
related_systems:
temporary_constraints:
```

## Context Hygiene
Review periodically for:
- expired dates;
- superseded campaign names;
- outdated access lists;
- obsolete deployment URLs;
- contradictory architecture;
- duplicated brand rules;
- credentials accidentally added.

## AI Instruction
Before executing a Rock City task:
1. read `START_HERE.md`;
2. load the files relevant to the task;
3. identify hard constraints;
4. identify time-sensitive facts requiring verification;
5. execute without re-inventing established context.
