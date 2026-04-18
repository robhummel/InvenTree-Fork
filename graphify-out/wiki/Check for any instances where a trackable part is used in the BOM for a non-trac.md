---
source_file: "inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L39"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# Check for any instances where a trackable part is used in the BOM for a non-trac

## Connections
- [[.update_trackable_status()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema