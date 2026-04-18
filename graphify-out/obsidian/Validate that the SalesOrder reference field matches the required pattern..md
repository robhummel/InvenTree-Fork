---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/order/validators.py"
type: "rationale"
community: "Community 2"
location: "L47"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Validate that the SalesOrder reference field matches the required pattern.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_sales_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2