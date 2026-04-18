---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Community 5"
location: "L249"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Check for parts with missing or outdated pricing information.      Tests for the

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[check_missing_pricing()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_5