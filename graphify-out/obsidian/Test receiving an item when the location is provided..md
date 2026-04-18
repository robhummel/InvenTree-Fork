---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/suppliers/test_supplier_barcodes.py"
type: "rationale"
community: "Core Models & Admin"
location: "L321"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Test receiving an item when the location is provided.

## Connections
- [[.test_receive_stock_location()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin