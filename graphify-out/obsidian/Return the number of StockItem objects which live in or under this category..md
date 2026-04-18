---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "Community 3"
location: "L322"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Return the number of StockItem objects which live in or under this category.

## Connections
- [[.stock_item_count()]] - `rationale_for` [EXTRACTED]
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