---
source_file: "inventree/src/backend/InvenTree/users/admin.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L148"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Custom admin interface for the Owner model.

## Connections
- [[ApiToken]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[OwnerAdmin]] - `rationale_for` [EXTRACTED]
- [[RuleSet]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking