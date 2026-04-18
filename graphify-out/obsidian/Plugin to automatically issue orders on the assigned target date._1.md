---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/events/auto_issue_orders.py"
type: "rationale"
community: "Community 3"
location: "L15"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Plugin to automatically issue orders on the assigned target date.

## Connections
- [[AutoIssueOrdersPlugin]] - `rationale_for` [EXTRACTED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[ReturnOrderStatus]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[SalesOrderStatus]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3