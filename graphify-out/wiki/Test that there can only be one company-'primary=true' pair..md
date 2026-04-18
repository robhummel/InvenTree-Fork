---
source_file: "inventree/src/backend/InvenTree/company/tests.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L203"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Test that there can only be one company-'primary=true' pair.

## Connections
- [[.test_primary_constraint()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings