---
source_file: "inventree/src/backend/InvenTree/company/test_supplier_parts.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L16"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Test valid values for the 'pack_quantity' field.

## Connections
- [[.test_pack_quantity_dimensionless()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeTestCase_1]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings