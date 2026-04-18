---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "Community 3"
location: "L4391"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Store and handle related parts (eg. mating connector, crimps, etc.).

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PartRelated]] - `rationale_for` [EXTRACTED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3