---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "Community 3"
location: "L3768"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# A BomItem links a part to its component items.      A part can have a BOM (bill

## Connections
- [[BomItem]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3