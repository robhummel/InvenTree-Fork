---
source_file: "inventree/src/backend/InvenTree/company/admin.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L60"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Admin class for the SupplierPriceBreak model.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[SalesOrderLineItemInlineAdmin]] - `rationale_for` [EXTRACTED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]
- [[SupplierPriceBreakAdmin]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings