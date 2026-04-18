---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Community 5"
location: "L162"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Check all stock items for stale stock.      This function runs daily and checks

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[check_stale_stock()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_5