---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/common/migrations/0010_migrate_currency_setting.py"
type: "rationale"
community: "Community 16"
location: "L8"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_16
---

# migrate the currency setting from config.yml to db

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[set_default_currency()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_16