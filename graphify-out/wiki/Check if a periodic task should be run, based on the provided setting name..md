---
source_file: "inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L82"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Check if a periodic task should be run, based on the provided setting name.

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[check_daily_holdoff()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes