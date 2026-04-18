---
source_file: "inventree/src/backend/InvenTree/company/admin.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L49"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Admin class for ManufacturerPart model.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[ManufacturerPartAdmin]] - `rationale_for` [EXTRACTED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings