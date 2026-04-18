---
source_file: "inventree/src/backend/InvenTree/InvenTree/test_tasks.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L32"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Ensure that duplicate tasks cannot be added.

## Connections
- [[.test_add_task()]] - `rationale_for` [EXTRACTED]
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[PluginRegistryMixin_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes