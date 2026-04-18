---
source_file: "inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L2833"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Return True if there are any 'required tests' associated with this StockItem.

## Connections
- [[.hasRequiredTests()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeCustomStatusModelField]] - `uses` [INFERRED]
- [[InvenTreeModelMoneyField]] - `uses` [INFERRED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StatusCodeMixin_1]] - `uses` [INFERRED]
- [[StockEvents]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]
- [[StockStatusGroups]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings