---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/api.py"
type: "rationale"
community: "Community 2"
location: "L35"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Custom view class for handling a barcode scan.

## Connections
- [[.post()]] - `rationale_for` [EXTRACTED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BarcodeView]] - `rationale_for` [EXTRACTED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[ImportRequestSerializer]] - `uses` [INFERRED]
- [[ImportResultSerializer]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[PartCategoryParameterTemplate]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]
- [[SearchResultSerializer]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[SupplierListSerializer]] - `uses` [INFERRED]
- [[SupplierMixin_1]] - `uses` [INFERRED]
- [[get_supplier_plugin()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2