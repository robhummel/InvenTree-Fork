---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/migrations/0058_auto_20211126_1210.py"
type: "rationale"
community: "Community 14"
location: "L9"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_14
---

# In migration 0057 we added a new field 'shipped' to the SalesOrderLineItem model

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[calculate_shipped_quantity()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_14