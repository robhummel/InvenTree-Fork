---
source_file: "inventree/src/backend/InvenTree/order/migrations/0055_auto_20211025_0645.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L61"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Reverse the migration, delete and SalesOrderShipment instances

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[reverse_add_shipment()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema