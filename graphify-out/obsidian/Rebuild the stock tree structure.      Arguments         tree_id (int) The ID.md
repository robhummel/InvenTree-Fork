---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/tasks.py"
type: "rationale"
community: "Core Models & Admin"
location: "L38"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Rebuild the stock tree structure.      Arguments:         tree_id (int): The ID

## Connections
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[rebuild_stock_item_tree()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin