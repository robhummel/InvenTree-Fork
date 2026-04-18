---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/tasks.py"
type: "rationale"
community: "Community 4"
location: "L213"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Create an AsyncTask if workers are running. This is different to a 'scheduled' t

## Connections
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeExchange]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[offload_task()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_4