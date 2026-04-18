---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Community 2"
location: "L130"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Handle barcode scan.          Arguments:             barcode: Raw barcode value

## Connections
- [[.handle_barcode()]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[CreateAPI_1]] - `uses` [INFERRED]
- [[DataImportSessionAcceptRows]] - `rationale_for` [EXTRACTED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[ListCreateAPI_1]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]
- [[RetrieveUpdateAPI_1]] - `uses` [INFERRED]
- [[RetrieveUpdateDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2