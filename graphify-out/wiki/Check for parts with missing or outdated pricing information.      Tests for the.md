---
source_file: "inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L249"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
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

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ