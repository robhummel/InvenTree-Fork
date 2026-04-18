---
source_file: "inventree/src/backend/InvenTree/plugin/models.py"
type: "rationale"
community: "Community 2"
location: "L283"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# This model represents settings for individual plugins.

## Connections
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[PluginEvents]] - `uses` [INFERRED]
- [[PluginSetting]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2