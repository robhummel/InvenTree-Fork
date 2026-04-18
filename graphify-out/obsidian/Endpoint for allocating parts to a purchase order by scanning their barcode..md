---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Community 2"
location: "L381"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Endpoint for allocating parts to a purchase order by scanning their barcode.

## Connections
- [[BarcodePOAllocate]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2