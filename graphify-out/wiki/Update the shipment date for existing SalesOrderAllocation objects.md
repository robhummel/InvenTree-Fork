---
source_file: "inventree/src/backend/InvenTree/order/migrations/0105_auto_20241128_0431.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L7"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Update the shipment date for existing SalesOrderAllocation objects

## Connections
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[update_shipment_date()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema