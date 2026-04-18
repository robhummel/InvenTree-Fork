---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Community 5"
location: "L137"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Check if the stock quantity has fallen below the minimum threshold of part.

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[notify_low_stock_if_required()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_5