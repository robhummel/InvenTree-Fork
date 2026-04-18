---
source_file: "inventree/src/backend/InvenTree/order/migrations/0058_auto_20211126_1210.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L9"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# In migration 0057 we added a new field 'shipped' to the SalesOrderLineItem model

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[calculate_shipped_quantity()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema