---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/validators.py"
type: "rationale"
community: "Community 2"
location: "L5"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Generate the next available SalesOrder reference.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[generate_next_sales_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2