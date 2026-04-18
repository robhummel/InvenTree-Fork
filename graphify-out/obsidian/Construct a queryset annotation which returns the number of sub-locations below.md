---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/filters.py"
type: "rationale"
community: "Community 3"
location: "L44"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_3
---

# Construct a queryset annotation which returns the number of sub-locations below

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_in_production_quantity()]] - `rationale_for` [EXTRACTED]
- [[annotate_sub_locations()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_3