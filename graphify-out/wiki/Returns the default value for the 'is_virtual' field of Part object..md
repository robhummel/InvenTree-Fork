---
source_file: "inventree/src/backend/InvenTree/part/settings.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L17"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Returns the default value for the 'is_virtual' field of Part object.

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[SystemSetId]] - `uses` [INFERRED]
- [[global_setting_overrides()]] - `rationale_for` [EXTRACTED]
- [[part_virtual_default()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema