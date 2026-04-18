---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/labels/inventree_machine.py"
type: "rationale"
community: "Community 1"
location: "L21"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Get the driver by machine pk and ensure that it is a label printing driver.

## Connections
- [[DependentField]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]
- [[LabelPrintingMixin_1]] - `uses` [INFERRED]
- [[LabelTemplate]] - `uses` [INFERRED]
- [[get_machine_and_driver()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_1