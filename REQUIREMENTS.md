# Requirements

Initial release: authenticated single-user workspace, Today, inbox, tasks with optional details, weekly planning, projects with next actions, work/personal/combined views, reusable lists, preferences and responsive layout. Supabase authentication and explicit grants and owner-scoped RLS policies required before real data. Disable public registration. Distinguish deadlines and intentions. Test access as anonymous and authenticated users.

Prototype uses fictional data and temporary in-memory interactions only.

## Daily rhythm and transitions (future)

Support configurable preferred work periods and task attention demands: responsive/administrative work, meetings, deep creative work, breaks and transitions. Use preferences as planning suggestions rather than fixed rules; actual commitments and user choices take precedence. Provide optional midday reorientation and an end-of-workday landing routine. Allow a configurable advance reminder and stopping time, with dismiss/snooze/adjust controls. Preserve continuation notes: progress, current context, next action and relevant resources. Optional voice capture and AI summarization require user review. Do not assume passive activity tracking or enforce stopping. Keep preferences private in the authenticated application, not public source code.

### Workday bookends

Support configurable opening and closing transition blocks (e.g., 30 minutes each). These are protected orientation and disengagement periods, not miscellaneous task execution windows. Opening brings forward daily orientation, intentions and workspace assembly. Closing brings forward continuation notes, loose-end capture and preparation for the next session (Tomorrow's Launchpad). Distinguish official work hours from a user-selected departure target; anchor closing to the latter when appropriate. Avoid filling transition blocks with additional tasks. Keep actual schedules and preferences private.

## Multimodal inbox capture

Provide mobile-friendly quick capture for typed text, links, audio dictation, recorded voice notes, video notes, and photos of handwritten material. Save first without requiring categorization. Optional AI transcription, OCR and extraction may propose separate inbox items, notes, tasks or ideas for user approval; never silently create commitments. Allow users to retain or delete original recordings independently of derived text. Use private authenticated media storage, explicit recording permissions, clear upload status and retry behavior. Test iOS Safari and installed PWA recording support; offer native dictation or file upload fallback. Audio capture and transcription should precede video in implementation unless user priorities change. Never capture confidential institutional or student records.
