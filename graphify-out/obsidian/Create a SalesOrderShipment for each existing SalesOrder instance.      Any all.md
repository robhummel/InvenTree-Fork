---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/migrations/0055_auto_20211025_0645.py"
type: "rationale"
community: "Inventory & Order Logic"
location: "L10"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Inventory_&_Order_Logic
---

# Create a SalesOrderShipment for each existing SalesOrder instance.      Any "all

## Connections
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[add_shipment()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Inventory_&_Order_Logic