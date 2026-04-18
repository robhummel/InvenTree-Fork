---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/management/commands/clean_settings.py"
type: "rationale"
community: "Core Models & Admin"
location: "L11"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Cleanup old (undefined) settings in the database.

## Connections
- [[Command_7]] - `rationale_for` [EXTRACTED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin