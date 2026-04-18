---
source_file: "inventree/src/backend/InvenTree/InvenTree/management/commands/clean_settings.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L11"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Cleanup old (undefined) settings in the database.

## Connections
- [[Command_7]] - `rationale_for` [EXTRACTED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeUserSetting]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes