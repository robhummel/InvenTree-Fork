---
source_file: "inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L296"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# A Contact represents a person who works at a particular company. A Company may h

## Connections
- [[Contact]] - `rationale_for` [EXTRACTED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings