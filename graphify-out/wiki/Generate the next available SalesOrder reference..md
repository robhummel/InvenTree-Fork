---
source_file: "inventree/src/backend/InvenTree/order/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L5"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Generate the next available SalesOrder reference.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[generate_next_sales_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking