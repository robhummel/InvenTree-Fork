---
source_file: "inventree/src/backend/InvenTree/company/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L1002"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Represents a quantity price break for a SupplierPart.      - Suppliers can offer

## Connections
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings