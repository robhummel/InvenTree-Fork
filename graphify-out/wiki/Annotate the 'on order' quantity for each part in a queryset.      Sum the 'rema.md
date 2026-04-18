---
source_file: "inventree/src/backend/InvenTree/part/filters.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L93"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Annotate the 'on order' quantity for each part in a queryset.      Sum the 'rema

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_on_order_quantity()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings