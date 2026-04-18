---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/migrations/0055_auto_20211025_0645.py"
type: "rationale"
community: "Inventory & Order Logic"
location: "L61"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Inventory_&_Order_Logic
---

# Reverse the migration, delete and SalesOrderShipment instances

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[reverse_add_shipment()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Inventory_&_Order_Logic