---
source_file: "inventree/src/backend/InvenTree/plugin/base/barcodes/serializers.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L207"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Serializr for allocating stock items to a sales order.      The scanned barcode

## Connections
- [[BarcodeSOAllocateSerializer]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings