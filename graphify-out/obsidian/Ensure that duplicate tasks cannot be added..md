---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/test_tasks.py"
type: "rationale"
community: "Core Models & Admin"
location: "L32"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
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

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin