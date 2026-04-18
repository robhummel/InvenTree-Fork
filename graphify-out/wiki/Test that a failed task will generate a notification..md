---
source_file: "inventree/src/backend/InvenTree/InvenTree/test_tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L190"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Test that a failed task will generate a notification.

## Connections
- [[.test_failed_task_notification()]] - `rationale_for` [EXTRACTED]
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[PluginRegistryMixin_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes