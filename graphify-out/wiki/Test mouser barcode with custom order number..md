---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/suppliers/test_supplier_barcodes.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L103"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Test mouser barcode with custom order number.

## Connections
- [[.test_mouser_barcode()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings