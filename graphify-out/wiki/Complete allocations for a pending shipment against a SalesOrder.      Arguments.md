---
source_file: "inventree/src/backend/InvenTree/order/tasks.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L246"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Complete allocations for a pending shipment against a SalesOrder.      Arguments

## Connections
- [[Owner]] - `uses` [INFERRED]
- [[PurchaseOrderEvents]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[ReturnOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderEvents]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[complete_sales_order_shipment()]] - `rationale_for` [EXTRACTED]
- [[envcheck_invoke_path()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings