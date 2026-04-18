---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/management/commands/clean_settings.py"
type: "rationale"
community: "Core Models & Admin"
location: "L1"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Custom management command to cleanup old settings that are not defined anymore.

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]
- [[clean_settings.py]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin