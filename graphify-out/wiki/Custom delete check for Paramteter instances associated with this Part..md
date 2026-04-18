---
source_file: "inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L572"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Custom delete check for Paramteter instances associated with this Part.

## Connections
- [[.check_parameter_delete()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings