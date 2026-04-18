---
source_file: "inventree/src/backend/InvenTree/part/filters.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L214"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Annotate the total quantity of each part required for sales orders.      - Only

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_sales_order_requirements()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings