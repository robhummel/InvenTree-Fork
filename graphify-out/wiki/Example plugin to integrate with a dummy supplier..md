---
source_file: "inventree/src/backend/InvenTree/plugin/samples/supplier/supplier_sample.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L12"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Example plugin to integrate with a dummy supplier.

## Connections
- [[Company]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[SampleSupplierPlugin]] - `rationale_for` [EXTRACTED]
- [[SupplierMixin_1]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings