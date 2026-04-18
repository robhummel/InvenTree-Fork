---
source_file: "inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L492"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Represents a unique part as provided by a Manufacturer Each ManufacturerPart is

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings