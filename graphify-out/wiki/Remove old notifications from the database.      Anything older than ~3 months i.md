---
source_file: "inventree/src/backend/InvenTree/common/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L41"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Remove old notifications from the database.      Anything older than ~3 months i

## Connections
- [[InvenTreeNotesMixin]] - `uses` [INFERRED]
- [[NewsFeedEntry]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[delete_old_notifications()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes