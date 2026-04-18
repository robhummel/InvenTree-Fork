---
source_file: "inventree/src/backend/InvenTree/company/admin.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L80"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Admin class for the Contact model.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ContactAdmin]] - `rationale_for` [EXTRACTED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]
- [[StockTrackingAdmin]] - `rationale_for` [EXTRACTED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ