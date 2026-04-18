---
source_file: "inventree/src/backend/InvenTree/order/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L47"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Validate that the SalesOrder reference field matches the required pattern.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_sales_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking