---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/mixins.py"
type: "rationale"
community: "Community 2"
location: "L42"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Does this plugin have everything needed to process a barcode.

## Connections
- [[.render_to_pdf()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[DataOutput]] - `uses` [INFERRED]
- [[InvenTreeBarcodeMixin]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[LabelTemplate]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[MixinNotImplementedError]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SettingsMixin_1]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2