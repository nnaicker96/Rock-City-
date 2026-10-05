# Digital Systems + Project Context

## Overall Architecture
Rock City’s digital environment should avoid one giant tool trying to own everything.

Preferred separation:
- Planning Center — ministry operations/system of record.
- Church Center — member-facing ministry interaction.
- Google Drive — files, documents, assets and shared folders.
- Notion / church operations layer — projects, actions, requests, meetings, decisions, SOPs and dashboards where adopted.
- GitHub — code, deployments, context packs and version history.
- Custom apps/microsites — targeted experience/operations layers.

## Church-Wide Operations Direction
A previous Tech Rock task-tracker evolved toward a **church-wide admin/operations platform**. Do not assume future operations tooling should be Tech Rock-only.

Needed capabilities discussed across task-system work include:
- workstreams;
- tasks/actions;
- owners;
- status;
- priority;
- deadlines;
- updates/notes/comments;
- team progress;
- personal views;
- actionable requests;
- links back to authoritative ministry records/documents.

## Notion Direction
A planned structure has included a top-level **Church Operations Hub** with concepts such as:
- Operations Home;
- Master Activity Register;
- Ministries & Groups database;
- SOPs;
- ministry structure;
- decisions;
- training;
- hardware inventory;
- exception queues.

Notion should complement Planning Center rather than duplicate its people/ministry database.

## Reporting Architecture
A prior reporting direction:
**emailed ministry reports → Google Drive folders → processor/structured dataset → dashboard**

Where automated reporting is used, maintain clear source provenance and human review for consequential decisions.

## T-Shirt / Catalogue Project
A separate Rock City web project has included:
- online catalogue;
- multiple sizes/items per order;
- name + sizes;
- Google Sheet data capture;
- optional payment gateway;
- pay-on-collection fallback;
- Netlify/static deployment;
- Apps Script endpoint;
- QR access.

This is project context, not a permanent architecture requirement.

## Custom Web Tool Rules
- Never hard-code credentials.
- Provide configuration/setup documentation.
- Use reliable data storage appropriate to the task.
- Test connections honestly.
- Do not claim a Sheet/API/database is updating unless verified.
- Custom apps must not bypass Planning Center safeguards or permissions.
