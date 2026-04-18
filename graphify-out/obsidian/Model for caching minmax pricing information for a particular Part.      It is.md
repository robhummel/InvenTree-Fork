---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "Community 3"
location: "L2707"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Model for caching min/max pricing information for a particular Part.      It is

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PartPricing]] - `rationale_for` [EXTRACTED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3