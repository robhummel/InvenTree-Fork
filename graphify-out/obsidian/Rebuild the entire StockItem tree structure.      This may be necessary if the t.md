---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/tasks.py"
type: "rationale"
community: "Community 1"
location: "L17"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Rebuild the entire StockItem tree structure.      This may be necessary if the t

## Connections
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[ping_machines()]] - `rationale_for` [EXTRACTED]
- [[rebuild_stock_items()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_1