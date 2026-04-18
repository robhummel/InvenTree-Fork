---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "Community 3"
location: "L1514"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Return True if this StockItem is allocated to a SalesOrder or a Build.

## Connections
- [[.is_allocated()]] - `rationale_for` [EXTRACTED]
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

#graphify/rationale #graphify/INFERRED #community/Community_3