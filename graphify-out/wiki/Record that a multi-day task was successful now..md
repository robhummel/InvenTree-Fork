---
source_file: "inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L158"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Record that a multi-day task was successful *now*.

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[record_task_success()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes