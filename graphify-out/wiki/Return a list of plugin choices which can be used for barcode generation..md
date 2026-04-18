---
source_file: "inventree/src/backend/InvenTree/common/setting/system.py"
type: "rationale"
community: "Community 2"
location: "L125"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Return a list of plugin choices which can be used for barcode generation.

## Connections
- [[InvenTreeSettingsKeyType]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[barcode_plugins()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2