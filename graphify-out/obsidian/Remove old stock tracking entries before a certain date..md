---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/tasks.py"
type: "rationale"
community: "Core Models & Admin"
location: "L77"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Remove old stock tracking entries before a certain date.

## Connections
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[delete_old_stock_tracking()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin