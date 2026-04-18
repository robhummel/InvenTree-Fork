---
source_file: "inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L4302"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Callback function when a part price break is created or updated.

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[update_pricing_after_edit()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings