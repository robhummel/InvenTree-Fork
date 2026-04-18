---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/events/auto_issue_orders.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L84"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Helper function to issue orders of a given model and status.

## Connections
- [[.issue_func()]] - `rationale_for` [EXTRACTED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[ReturnOrderStatus]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[SalesOrderStatus]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings