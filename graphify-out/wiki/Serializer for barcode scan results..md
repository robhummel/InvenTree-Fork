---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/serializers.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L22"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Serializer for barcode scan results.

## Connections
- [[BarcodeScanResultSerializer]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings