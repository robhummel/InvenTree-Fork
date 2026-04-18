---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "Community 3"
location: "L2675"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Returns True if the total stock for this part is less than the minimum stock lev

## Connections
- [[.is_part_low_on_stock()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3