---
source_file: "inventree/src/backend/InvenTree/order/migrations/0055_auto_20211025_0645.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L10"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Create a SalesOrderShipment for each existing SalesOrder instance.      Any "all

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[add_shipment()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema