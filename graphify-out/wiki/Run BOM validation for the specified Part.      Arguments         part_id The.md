---
source_file: "inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L414"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Run BOM validation for the specified Part.      Arguments:         part_id: The

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[validate_bom()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ