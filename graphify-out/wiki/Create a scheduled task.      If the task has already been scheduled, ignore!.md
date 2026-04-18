---
source_file: "inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L42"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Create a scheduled task.      If the task has already been scheduled, ignore!

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[is_docker_environment()]] - `rationale_for` [EXTRACTED]
- [[schedule_task()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes