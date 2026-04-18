---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/test_barcode.py"
type: "rationale"
community: "Core Models & Admin"
location: "L162"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Test that a barcode is generated with a scan.

## Connections
- [[.test_barcode_scan()]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin