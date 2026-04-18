---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Community 4"
location: "L770"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Returns a list of migrations which are needed to be run.

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[get_migration_plan()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_4