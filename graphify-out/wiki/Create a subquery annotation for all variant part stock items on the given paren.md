---
source_file: "inventree/src/backend/InvenTree/part/filters.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L292"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Create a subquery annotation for all variant part stock items on the given paren

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_variant_quantity()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings