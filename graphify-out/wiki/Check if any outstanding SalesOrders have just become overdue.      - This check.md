---
source_file: "inventree/src/backend/InvenTree/order/tasks.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L142"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Check if any outstanding SalesOrders have just become overdue.      - This check

## Connections
- [[Owner]] - `uses` [INFERRED]
- [[PurchaseOrderEvents]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[ReturnOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderEvents]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[check_overdue_sales_orders()]] - `rationale_for` [EXTRACTED]
- [[task_exception_handler()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings