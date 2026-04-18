---
source_file: "inventree/src/backend/InvenTree/stock/tasks.py"
type: "rationale"
community: "Deployment & Docker Architecture"
location: "L77"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Deployment_&_Docker_Architecture
---

# Remove old stock tracking entries before a certain date.

## Connections
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[delete_old_stock_tracking()]] - `rationale_for` [EXTRACTED]
- [[get_inventree_api_version()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Deployment_&_Docker_Architecture