---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/serializers.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L59"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Serializer for generating a barcode.

## Connections
- [[BarcodeGenerateSerializer]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings