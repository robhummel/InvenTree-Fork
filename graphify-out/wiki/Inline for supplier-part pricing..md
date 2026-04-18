---
source_file: "inventree/src/backend/InvenTree/company/admin.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L29"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Inline for supplier-part pricing.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]
- [[SupplierPriceBreakInline]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings