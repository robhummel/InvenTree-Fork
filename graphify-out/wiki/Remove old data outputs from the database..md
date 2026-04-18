---
source_file: "inventree/src/backend/InvenTree/common/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L29"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Remove old data outputs from the database.

## Connections
- [[InvenTreeNotesMixin]] - `uses` [INFERRED]
- [[NewsFeedEntry]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[cleanup_old_data_outputs()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes