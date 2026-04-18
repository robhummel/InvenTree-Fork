---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "Community 3"
location: "L957"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Return the total quantity of items currently on order.          Subtract partial

## Connections
- [[.on_order()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3