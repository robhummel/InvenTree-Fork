---
source_file: "inventree/src/backend/InvenTree/order/test_migrations.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L204"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Test data migration which fixes empty 'shipment date' on SalesOrder model.

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[TestShipmentDateMigration]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema