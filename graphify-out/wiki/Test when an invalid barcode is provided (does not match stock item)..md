---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/test_barcode.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L325"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Test when an invalid barcode is provided (does not match stock item).

## Connections
- [[.test_invalid_barcode()]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ