---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/mixins.py"
type: "rationale"
community: "Community 2"
location: "L111"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Return the value of a barcode field.

## Connections
- [[.get_field_value()]] - `rationale_for` [EXTRACTED]
- [[.print_labels()_2]] - `rationale_for` [EXTRACTED]
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