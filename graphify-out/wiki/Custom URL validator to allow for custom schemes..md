---
source_file: "inventree/src/backend/InvenTree/InvenTree/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L57"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Custom URL validator to allow for custom schemes.

## Connections
- [[AllowedURLValidator]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking