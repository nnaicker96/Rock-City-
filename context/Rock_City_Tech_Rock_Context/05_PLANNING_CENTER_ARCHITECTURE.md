# Planning Center — Rock City Architecture

## Role
Planning Center is the primary operational system of record for ministry data and participation workflows.

## Product Responsibilities

### People
Central people/household database.
Use for:
- person records;
- households;
- contact information;
- data quality;
- authorised lists/workflows where appropriate.

### Groups
Primary ministry structure for many ministries.
Use for:
- ministry/group membership;
- leaders;
- group events;
- RSVP;
- resources;
- recurring community/ministry structures.

### Services
Use for actual service planning and rostering where appropriate.
Current/established principle:
- Worship is the principal Services rollout/pilot.
- Service plans must reflect real service structures.
- Two vocal positions are required per relevant plan.
- Do not move every ministry into Services merely because it exists.

### Calendar
Church-wide events and resource/calendar coordination.
The official Rock City calendar is the source of truth for church dates.

### Registrations / Forms
Use for sign-ups, registrations and structured intake where appropriate.

### Check-Ins
Especially important for Kids Rock and safeguarding/attendance.
Do not bypass secure child check-in requirements with a custom app merely for convenience.

### Publishing / Church Center
Member-facing layer.
Main navigation previously established:
- Home
- Groups
- Signups
- Me

Home tiles/context has included:
- Info Hub
- Sermons
- Devotionals
- About Us

Info Hub direction:
- open directly to Key Dates;
- avoid redundant church info/location/directions where previously removed;
- previous sermons/SoundCloud can sit lower in the experience.

## Groups vs Services
Use the right product for the job:
- **Groups** = belonging, ministry structure, group events, RSVP, resources.
- **Services** = specific service plans, teams, positions, scheduling/rostering.
- **Calendar** = church-wide event/resource visibility.
- **Check-Ins** = safeguarding/attendance use cases, especially children.

## Sunday Event Rule
For group/event structures:
- one Sunday service = one event;
- two services = separate `08:00` and `10:00` events;
- never collapse two distinct services into one combined event.

## Current Rollout Logic
The rollout has been Groups-first for administrators/ministry leaders, with selective Services adoption rather than indiscriminate backend access.

## Access Principle
Most people should use Church Center, not backend Planning Center.

## System Integration Principle
Planning actions, requests and owners must have a real system location. Avoid creating a disconnected “task layer” that has no relationship to ministry records, documents, decisions or accountable owners.

A broader operating model may use:
- Planning Center = ministry system of record;
- Notion/operations layer = projects, actions, requests, meetings, decisions, dashboards;
- Google Drive = documents/assets/working files.

## Do Not
- bypass Planning Center permissions;
- duplicate sensitive people data unnecessarily;
- replace child safeguarding workflows with convenience tools;
- combine separate services;
- grant broad backend access by default;
- treat Church Center and Planning Center backend as the same user experience.
