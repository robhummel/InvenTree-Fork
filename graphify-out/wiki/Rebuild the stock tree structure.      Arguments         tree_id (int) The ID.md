---
source_file: "inventree/src/backend/InvenTree/stock/tasks.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L38"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Rebuild the stock tree structure.      Arguments:         tree_id (int): The ID

## Connections
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[rebuild_stock_item_tree()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ