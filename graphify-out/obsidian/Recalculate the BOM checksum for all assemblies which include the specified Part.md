---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Community 5"
location: "L392"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Recalculate the BOM checksum for all assemblies which include the specified Part

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[check_bom_valid()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_5