---
source_file: "inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L287"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Return a list of all stock items supplied or manufactured by this company.

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings