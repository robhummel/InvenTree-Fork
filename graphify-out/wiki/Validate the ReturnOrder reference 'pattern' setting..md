---
source_file: "inventree/src/backend/InvenTree/order/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L40"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Validate the ReturnOrder reference 'pattern' setting.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_return_order_reference_pattern()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking