---
source_file: "inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L1582"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Return the quantity of this StockItem which is *not* allocated.

## Connections
- [[.unallocated_quantity()]] - `rationale_for` [EXTRACTED]
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