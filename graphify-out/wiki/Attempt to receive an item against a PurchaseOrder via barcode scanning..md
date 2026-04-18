---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/mixins.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L324"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Attempt to receive an item against a PurchaseOrder via barcode scanning.

## Connections
- [[.scan_receive_item()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeBarcodeMixin]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SettingsMixin_1]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings