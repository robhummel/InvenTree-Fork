---
source_file: "inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L216"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Return the total part count under this category (including children of child cat

## Connections
- [[.partcount()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Meta]] - `rationale_for` [EXTRACTED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings