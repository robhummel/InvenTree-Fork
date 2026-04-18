---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/common/tasks.py"
type: "rationale"
community: "Core Models & Admin"
location: "L116"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Remove old notes images from the database.      Anything older than ~3 months is

## Connections
- [[InvenTreeNotesMixin]] - `uses` [INFERRED]
- [[NewsFeedEntry]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[delete_old_notes_images()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin