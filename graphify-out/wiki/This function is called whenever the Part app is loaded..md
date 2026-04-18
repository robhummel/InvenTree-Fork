---
source_file: "inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L20"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# This function is called whenever the Part app is loaded.

## Connections
- [[.ready()_6]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema