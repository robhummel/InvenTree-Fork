---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L327"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Endpoint for unlinking / unassigning a custom barcode from a database object.

## Connections
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BarcodeUnassign]] - `rationale_for` [EXTRACTED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking