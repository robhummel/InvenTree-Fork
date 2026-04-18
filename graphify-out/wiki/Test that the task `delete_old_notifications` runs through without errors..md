---
source_file: "inventree/src/backend/InvenTree/common/test_tasks.py"
type: "rationale"
community: "Community 2"
location: "L16"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Test that the task `delete_old_notifications` runs through without errors.

## Connections
- [[.test_delete()]] - `rationale_for` [EXTRACTED]
- [[NewsFeedEntry]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2