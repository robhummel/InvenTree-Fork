---
source_file: "inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L60"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# Performed on startup, to ensure that all pricing objects are in a "good" state.

## Connections
- [[.reset_part_pricing_flags()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema