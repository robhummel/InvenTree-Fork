---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/events/auto_issue_orders.py"
type: "rationale"
community: "Community 3"
location: "L84"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
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

#graphify/rationale #graphify/INFERRED #community/Community_3