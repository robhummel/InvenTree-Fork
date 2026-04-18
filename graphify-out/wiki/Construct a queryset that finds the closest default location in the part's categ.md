---
source_file: "inventree/src/backend/InvenTree/part/filters.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L341"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Construct a queryset that finds the closest default location in the part's categ

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_default_location()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings