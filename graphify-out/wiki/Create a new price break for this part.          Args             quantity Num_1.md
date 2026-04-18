---
source_file: "inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L936"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Create a new price break for this part.          Args:             quantity: Num

## Connections
- [[.add_price_break()_1]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings