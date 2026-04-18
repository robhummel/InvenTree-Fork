---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Community 4"
location: "L372"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# A scheduled task.      - interval: The interval at which the task should be run

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[ScheduledTask]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_4