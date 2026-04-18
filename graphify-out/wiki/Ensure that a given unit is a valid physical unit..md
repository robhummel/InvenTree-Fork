---
source_file: "inventree/src/backend/InvenTree/InvenTree/validators.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L16"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Ensure that a given unit is a valid physical unit.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_physical_units()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking