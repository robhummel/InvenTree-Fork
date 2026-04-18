---
source_file: "inventree/src/backend/InvenTree/part/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L771"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Check the 'revision' and 'revision_of' fields.

## Connections
- [[.validate_revision()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings