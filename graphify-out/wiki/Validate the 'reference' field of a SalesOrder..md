---
source_file: "inventree/src/backend/InvenTree/InvenTree/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L87"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Validate the 'reference' field of a SalesOrder.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_sales_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking