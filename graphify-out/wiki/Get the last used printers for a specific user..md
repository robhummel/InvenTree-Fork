---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/labels/inventree_machine.py"
type: "rationale"
community: "Community 2"
location: "L41"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Get the last used printers for a specific user.

## Connections
- [[DependentField]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]
- [[LabelPrintingMixin_1]] - `uses` [INFERRED]
- [[LabelTemplate]] - `uses` [INFERRED]
- [[get_last_used_printers()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2