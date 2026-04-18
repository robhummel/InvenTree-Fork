---
source_file: "inventree/src/backend/InvenTree/plugin/test_plugin.py"
type: "rationale"
community: "Community 2"
location: "L370"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Test that a plugin cannot override the is_mandatory method.

## Connections
- [[.test_plugin_override_mandatory()]] - `rationale_for` [EXTRACTED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[NoIntegrationPlugin]] - `uses` [INFERRED]
- [[PluginConfig]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[PluginRegistryMixin_1]] - `uses` [INFERRED]
- [[SampleIntegrationPlugin]] - `uses` [INFERRED]
- [[TestQueryMixin_1]] - `uses` [INFERRED]
- [[WrongIntegrationPlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2