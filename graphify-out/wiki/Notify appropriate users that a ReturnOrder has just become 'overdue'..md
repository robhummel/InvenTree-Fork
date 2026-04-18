---
source_file: "inventree/src/backend/InvenTree/order/tasks.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L174"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Notify appropriate users that a ReturnOrder has just become 'overdue'.

## Connections
- [[Owner]] - `uses` [INFERRED]
- [[PurchaseOrderEvents]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[ReturnOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderEvents]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[notify_overdue_return_order()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings