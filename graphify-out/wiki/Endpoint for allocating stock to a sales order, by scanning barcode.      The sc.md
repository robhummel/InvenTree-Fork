---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L588"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Endpoint for allocating stock to a sales order, by scanning barcode.      The sc

## Connections
- [[BarcodeSOAllocate]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking