---
source_file: "inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L15"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# Config class for the 'part' app.

## Connections
- [[BomItem]] - `uses` [INFERRED]
- [[CommonConfig]] - `rationale_for` [EXTRACTED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartConfig]] - `rationale_for` [EXTRACTED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema