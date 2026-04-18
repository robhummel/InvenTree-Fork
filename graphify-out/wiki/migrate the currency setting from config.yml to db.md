---
source_file: "inventree/src/backend/InvenTree/common/migrations/0010_migrate_currency_setting.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L8"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Part_Management_&_Archetypes
---

# migrate the currency setting from config.yml to db

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[set_default_currency()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Part_Management_&_Archetypes