---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/events/auto_issue_orders.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L1"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Plugin to automatically issue orders on the assigned target date.

## Connections
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[ReturnOrderStatus]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[auto_issue_orders.py]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings