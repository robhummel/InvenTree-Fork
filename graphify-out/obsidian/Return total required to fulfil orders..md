---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "Community 3"
location: "L1490"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Return total required to fulfil orders.

## Connections
- [[.required_order_quantity()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3