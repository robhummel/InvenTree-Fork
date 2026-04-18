---
source_file: "inventree/src/backend/InvenTree/common/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L61"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Return the model class for the given label.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[ReturnOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[attachment_model_class_from_label()]] - `rationale_for` [EXTRACTED]
- [[validate_return_order_reference()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking