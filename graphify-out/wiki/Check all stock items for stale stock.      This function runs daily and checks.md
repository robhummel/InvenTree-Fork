---
source_file: "inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L162"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
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

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ