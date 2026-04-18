---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "Community 3"
location: "L2868"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Hook function to be executed after StockItem object is saved/updated.

## Connections
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
- [[after_save_stock_item()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_3