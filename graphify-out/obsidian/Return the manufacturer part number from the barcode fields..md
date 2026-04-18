---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/mixins.py"
type: "rationale"
community: "Community 4"
location: "L172"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Return the manufacturer part number from the barcode fields.

## Connections
- [[.create_related_parts()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeBarcodeMixin]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SettingsMixin_1]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_4