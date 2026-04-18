---
source_file: "inventree/src/backend/InvenTree/common/setting/system.py"
type: "rationale"
community: "Community 2"
location: "L101"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# When a core plugin setting is changed, reload the plugin registry.

## Connections
- [[InvenTreeSettingsKeyType]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[reload_plugin_registry()_1]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2