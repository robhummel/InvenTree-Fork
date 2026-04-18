---
source_file: "inventree/src/backend/InvenTree/generic/states/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L12"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Initialize the validator.

## Connections
- [[.__init__()_48]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[generate_next_purchase_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking