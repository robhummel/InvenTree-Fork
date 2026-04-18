---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/filters.py"
type: "rationale"
community: "Community 3"
location: "L214"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Annotate the total quantity of each part required for sales orders.      - Only

## Connections
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[annotate_sales_order_requirements()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_3