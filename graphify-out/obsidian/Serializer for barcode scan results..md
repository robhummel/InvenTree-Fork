---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/serializers.py"
type: "rationale"
community: "Community 3"
location: "L22"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Serializer for barcode scan results.

## Connections
- [[BarcodeScanResultSerializer]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3