---
source_file: "inventree/src/backend/InvenTree/stock/filters.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L44"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Construct a queryset annotation which returns the number of sub-locations below

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_in_production_quantity()]] - `rationale_for` [EXTRACTED]
- [[annotate_sub_locations()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema