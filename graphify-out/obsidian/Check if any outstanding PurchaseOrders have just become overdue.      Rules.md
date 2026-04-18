---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/tasks.py"
type: "rationale"
community: "Community 3"
location: "L72"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Check if any outstanding PurchaseOrders have just become overdue.      Rules:

## Connections
- [[Owner]] - `uses` [INFERRED]
- [[PurchaseOrderEvents]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[ReturnOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderEvents]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[check_overdue_purchase_orders()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_3