---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Community 2"
location: "L327"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Endpoint for unlinking / unassigning a custom barcode from a database object.

## Connections
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BarcodeUnassign]] - `rationale_for` [EXTRACTED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2