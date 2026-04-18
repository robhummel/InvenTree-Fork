---
source_file: "inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L777"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Returns the number of all detected migrations.

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[get_migration_count()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes