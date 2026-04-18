---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/validators.py"
type: "rationale"
community: "Community 2"
location: "L16"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Ensure that a given unit is a valid physical unit.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[validate_physical_units()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_2