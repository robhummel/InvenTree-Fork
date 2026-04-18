---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/company/admin.py"
type: "rationale"
community: "Core Models & Admin"
location: "L36"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Admin class for the SupplierPart model.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[LocationTypeAdmin]] - `rationale_for` [EXTRACTED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[SelectionListEntryInlineAdmin]] - `rationale_for` [EXTRACTED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPartAdmin]] - `rationale_for` [EXTRACTED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin