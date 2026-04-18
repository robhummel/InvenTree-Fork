---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/common/models.py"
type: "rationale"
community: "Community 4"
location: "L2835"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Model for storing barcode scans results.

## Connections
- [[BarcodeScanResult]] - `rationale_for` [EXTRACTED]
- [[ColorEnum]] - `uses` [INFERRED]
- [[InvenTreeAttachmentMixin]] - `uses` [INFERRED]
- [[InvenTreeParameterMixin]] - `uses` [INFERRED]
- [[InvenTreeSettingsKeyType]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[SettingsKeyType_2]] - `uses` [INFERRED]
- [[StatusCode_1]] - `uses` [INFERRED]
- [[StringEnum_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_4