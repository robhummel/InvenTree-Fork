---
source_file: "inventree/src/backend/InvenTree/common/models.py"
type: "rationale"
community: "Community 2"
location: "L3019"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Model for storing email messages sent or received by the system.      Attributes

## Connections
- [[ColorEnum]] - `uses` [INFERRED]
- [[EmailMessage]] - `rationale_for` [EXTRACTED]
- [[InvenTreeAttachmentMixin]] - `uses` [INFERRED]
- [[InvenTreeParameterMixin]] - `uses` [INFERRED]
- [[InvenTreeSettingsKeyType]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[SettingsKeyType_2]] - `uses` [INFERRED]
- [[StatusCode_1]] - `uses` [INFERRED]
- [[StringEnum_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2